Got it! Let’s translate the same concept—using an abstract class vs interface—into a recharge app scenario.

Scenario: Recharge App
Your app supports multiple Recharge Providers (like Airtel, Vodafone, etc.). Every provider:

Has a provider name.

Can perform a recharge operation.

Has a method to validate the recharge amount (rules may vary).

Using an Abstract Class in C#
csharp
Copy
Edit
// Abstract base class with common fields and methods
public abstract class RechargeProvider
{
    public string ProviderName { get; private set; }

    public RechargeProvider(string providerName)
    {
        ProviderName = providerName;
    }

    // Common method shared by all providers
    public void LogTransaction(decimal amount)
    {
        Console.WriteLine($"Transaction logged for {ProviderName} with amount: {amount}");
    }

    // Abstract methods to be implemented by each provider
    public abstract bool ValidateAmount(decimal amount);
    public abstract void Recharge(decimal amount);
}

// Airtel provider
public class AirtelProvider : RechargeProvider
{
    public AirtelProvider() : base("Airtel") {}

    public override bool ValidateAmount(decimal amount)
    {
        // Airtel only allows recharges between 10 and 1000
        return amount >= 10 && amount <= 1000;
    }

    public override void Recharge(decimal amount)
    {
        if (!ValidateAmount(amount))
        {
            Console.WriteLine("Invalid amount for Airtel recharge.");
            return;
        }
        Console.WriteLine($"Recharging {amount} to Airtel.");
        LogTransaction(amount);
    }
}

// Vodafone provider
public class VodafoneProvider : RechargeProvider
{
    public VodafoneProvider() : base("Vodafone") {}

    public override bool ValidateAmount(decimal amount)
    {
        // Vodafone allows recharge from 20 to 1500
        return amount >= 20 && amount <= 1500;
    }

    public override void Recharge(decimal amount)
    {
        if (!ValidateAmount(amount))
        {
            Console.WriteLine("Invalid amount for Vodafone recharge.");
            return;
        }
        Console.WriteLine($"Recharging {amount} to Vodafone.");
        LogTransaction(amount);
    }
}
Using an Interface in C#
csharp
Copy
Edit
public interface IRechargeProvider
{
    string ProviderName { get; }
    bool ValidateAmount(decimal amount);
    void Recharge(decimal amount);
    void LogTransaction(decimal amount);
}

public class AirtelProvider : IRechargeProvider
{
    public string ProviderName => "Airtel";

    public bool ValidateAmount(decimal amount)
    {
        return amount >= 10 && amount <= 1000;
    }

    public void Recharge(decimal amount)
    {
        if (!ValidateAmount(amount))
        {
            Console.WriteLine("Invalid amount for Airtel recharge.");
            return;
        }
        Console.WriteLine($"Recharging {amount} to Airtel.");
        LogTransaction(amount);
    }

    public void LogTransaction(decimal amount)
    {
        Console.WriteLine($"Transaction logged for Airtel with amount: {amount}");
    }
}

public class VodafoneProvider : IRechargeProvider
{
    public string ProviderName => "Vodafone";

    public bool ValidateAmount(decimal amount)
    {
        return amount >= 20 && amount <= 1500;
    }

    public void Recharge(decimal amount)
    {
        if (!ValidateAmount(amount))
        {
            Console.WriteLine("Invalid amount for Vodafone recharge.");
            return;
        }
        Console.WriteLine($"Recharging {amount} to Vodafone.");
        LogTransaction(amount);
    }

    public void LogTransaction(decimal amount)
    {
        Console.WriteLine($"Transaction logged for Vodafone with amount: {amount}");
    }
}
Why Abstract Class Is Better Here:
The LogTransaction method logic is shared and written once.

The ProviderName property is maintained in one place.

You avoid repeating common code in every provider.

Each provider only focuses on its own validation and recharge logic.
