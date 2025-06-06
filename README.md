An abstract class vs interface—into a recharge app scenario.

Scenario: Recharge App
Your app supports multiple Recharge Providers (like Airtel, Vodafone, etc.). Every provider:

Has a provider name.

Can perform a recharge operation.

Has a method to validate the recharge amount (rules may vary).

Using an Abstract Class in C#
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


**1. What is .NET Core?** <br>
.NET Core is a cross-platform, open-source framework for building modern, cloud-based, and internet-connected applications. It supports Windows, Linux, and macOS.

**2. What is the difference between IServiceCollection and IServiceProvider?** <br>
IServiceCollection is used to register services and configure dependency injection. IServiceProvider is used to resolve and provide service instances at runtime.

**3. What are the main differences between .NET Core and .NET Framework?** <br>
• .NET Core is cross-platform; .NET Framework is Windows-only.
• .NET Core is open-source; .NET Framework is not fully open-source.
• .NET Core supports side-by-side versioning; .NET Framework does not.

**4. What is Dependency Injection in .NET Core?** <br>
Dependency Injection (DI) is a design pattern used to achieve Inversion of Control (IoC) between classes and their dependencies. .NET Core has built-in support for DI via the IServiceCollection and IServiceProvider.

**5. What is Middleware in ASP.NET Core?** <br>
Middleware is software that is assembled into an application pipeline to handle requests and responses. Each middleware component can process requests, pass them to the next component, or short-circuit the pipeline.

**6. How do you configure services in .NET Core?** <br>
Services are configured in the Program.cs or Startup.cs file using the IServiceCollection interface, typically in the ConfigureServices method.

**7. What is the purpose of the appsettings.json file?** <br>
appsettings.json is used to store configuration data such as connection strings, app settings, and logging configuration. It supports hierarchical data and can be loaded into the configuration system.

**8. How do you implement logging in .NET Core?** <br>
.NET Core provides built-in logging via the ILogger<T> interface. You can log information, warnings, errors, etc., and integrate with providers like Console, Debug, Serilog, NLog, etc.

**9. What is Kestrel?** <br>
Kestrel is a cross-platform web server for ASP.NET Core applications. It is the default web server and is designed for high performance.

**10. How do you enable CORS in ASP.NET Core?** <br>
CORS (Cross-Origin Resource Sharing) can be enabled by adding services with services.AddCors() and configuring policies in Configure using app.UseCors().

**11. What is Entity Framework Core?** <br>
Entity Framework Core (EF Core) is an ORM (Object-Relational Mapper) for .NET Core. It allows developers to work with databases using .NET objects, supports LINQ queries, and handles database migrations.

**12. What are the lifetimes of services in .NET Core DI?** <br>
• Singleton: One instance for the entire application.
• Scoped: One instance per HTTP request.
• Transient: A new instance every time the service is requested.

**13. How do you implement custom middleware in ASP.NET Core?** <br>
Create a class with an Invoke or InvokeAsync method that takes HttpContext as a parameter. Register it in the pipeline using app.UseMiddleware<YourMiddleware>().

**14. What is the purpose of the app.UseRouting() and app.UseEndpoints() methods?** <br>
app.UseRouting() enables routing capabilities.
app.UseEndpoints() defines the endpoints for the app (e.g., controllers, Razor Pages).

**15. How do you handle configuration in .NET Core?** <br>
.NET Core uses the IConfiguration interface to read configuration from various sources like appsettings.json, environment variables, and command-line arguments.

**16. What is the difference between appsettings.json and appsettings.Development.json?** <br>
appsettings.json contains default configuration.
appsettings.Development.json overrides settings for the Development environment.

**17. How do you enable HTTPS redirection in ASP.NET Core?** <br>
By calling app.UseHttpsRedirection() in the middleware pipeline.

**18. What is Model Binding in ASP.NET Core?** <br>
Model binding maps data from HTTP requests (route, query string, form, body) to action method parameters.

**19. How do you return different HTTP status codes from a controller action?** <br>
Use built-in methods like Ok(), BadRequest(), NotFound(), Created(), etc., or return an IActionResult with a specific status code.

**20. What is the purpose of IHostedService?** <br>
IHostedService is used to run background tasks in ASP.NET Core, such as consuming messages from a queue or scheduled jobs.
