# Dot Net Full Stack Developer Interview Questions

> By [Manoj Kumar](https://in.linkedin.com/in/mansun7)

**🚀** Innovative Tech Lead | Fintech Architect | Cloud & Microservices Expert | .NET & Azure Specialist | .NET Core | Web API | SQL Server | Scalable Architecture

## Table of contents
- [C# Programming](#c-programming)
- [ASP.NET & ASP.NET MVC](#aspnet--aspnet-mvc)
- [Features](#features)
- [Sponsors 🏆](#sponsors)
- [**Build your website in 3 steps**](#build-your-website-in-3-steps)
- [Plans](#plans)
- [Add your own content](#add-your-own-content)
- [Customizing parameters for each page](#customizing-parameters-for-each-page)
- [Supported parameters](#supported-parameters)
- [Featured users (success stories!)](#featured-users-success-stories)
- [Next steps](#next-steps)
- [Getting help](#getting-help)
- [Credits and contributions](#contributions)

# C Programming
we are working

# ASP.NET & ASP.NET MVC
mvc here

# Features

__Check out [*What's New?*](https://beautifuljekyll.com/updates/) to see the latest features!__

- **SIMPLE**: The primary goal of Beautiful Jekyll is to allow literally *anyone* to create a website in a few minutes.
- **Modern**: Uses the latest best practices and technologies to achieve nearly perfect scores on Google Chrome's Audit.
- **Mobile-first**: Designed to look great on both large-screen and small-screen (mobile) devices.
- **Highly customizable**: Many personalization settings such as changing the background colour/image, adding a logo.
- **Flexible usage**: Use Beautiful Jekyll directly on GitHub or via a Ruby gem - choose the best [development method](#build-your-website-in-3-steps) for you.
- **Battle-tested**: By using Beautiful Jekyll, you'll be joining 50,000+ users enjoying this theme since 2015.
- **SEO and social media support**: Customize how your site looks on Google and when shared on social media.
- **Comments support**: Add comments to any page using either [Disqus](https://disqus.com/), [Facebook comments](https://developers.facebook.com/docs/plugins/comments), [Utterances](https://utteranc.es/), [Staticman](https://staticman.net), [giscus](https://giscus.app), or [CommentBox](https://commentbox.io/).
- **Tags**: Any blog post can be tagged with keywords, and an index page is automatically generated.
- **Analytics**: Easily integrate Google Analytics, or other analytics platforms, to track visits to your website.
- **Search**: Let users easily find any page using a Search button in the navigation bar.
- **Photos support**: Any page can have a full-width cover photo and thumbnail.
- **RSS**: An RSS feed is automatically created, so you can even host a podcast easily with Beautiful Jekyll.

<h2 id="sponsors">Sponsors 🏆</h2>

Developing and maintaining Beautiful Jekyll takes a lot of time and effort - thank you to anyone who helps fund this effort!

- [DoFollow](https://dofollow.co.uk/)
- [Varna Sri Raman](https://about.me/varna)

**[Become a sponsor for Beautiful Jekyll and unlock new features\!](https://github.com/sponsors/daattali/sponsorships?tier_id=39856)**

# Build your website in 3 steps

There are a few different ways to build a website using Beautiful Jekyll, and this document will go through the simplest one: using a fork on GitHub. For most people (including myself!), this easy method is the recommended one.

Even if you choose to use one of the [advanced installation methods](https://beautifuljekyll.com/getstarted/#install-steps-hard), I still suggest you read through the easy method first.

## The easy way (recommended!)

Getting started is *literally* as easy as 1-2-3 :smile:

Scroll down to see the steps involved, but here is a 30-second video just as a reference as you work through the steps. If you don't already have a [GitHub account](https://github.com), you'll need to sign up.

![Installation steps](https://beautifuljekyll.com/assets/img/install-steps.gif)

### 1. Fork this project

Click on the __*Fork*__ button at the top right corner of this page. Forking means that you're copying this entire project and all its files into your account. Do not click on the __*Create fork*__ button on the next page yet.

### 2. Rename the repository to `YOURUSERNAME.github.io`

You'll see the word "repository" used a lot in GitHub - it simply means "project". Under __*Repository name*__ you should see the name `beautiful-jekyll`, this is where you need to rename your project to `YOURUSERNAME.github.io` (replace `YOURUSERNAME` with your GitHub user name). It's important to use this exact name so that GitHub will recognize it and automatically create a website for this project.   

> Tip: If you want to use a different URL for your website, check out the [FAQ](https://beautifuljekyll.com/faq/#custom-domain)
 
### 3. Customize your website settings

Edit the `_config.yml` file to change any settings you want. To edit the file, first click on it to view the file, and on the next page click on the pencil icon to edit it (watch the video tutorial above if you're confused).  The settings in the file are self-explanatory and there are comments inside the file to help you understand what each setting does. Any line that begins with a hashtag (`#`) is a comment, and the other lines are actual settings. After changing the settings, click the green __*Commit changes*__ button to save these edits.

> Note: In the video above, only one setting in the `_config.yml` file is edited, but you should go through the rest of the settings as well.

### 4. Congratulations! You have a website!

If you named your project correctly and made an edit to the config file, your website should be ready in a minute or two at `https://YOURUSERNAME.github.io`. Every time you make a change to any file, your website will get rebuilt and should be updated in about a minute or so. Your website will be initialized with several sample blog posts and a couple other pages.

## The harder way (for advanced users)

The instructions above explain how to use Beautiful Jekyll in the easiest way: by forking on GitHub. There are more [advanced installation methods](https://beautifuljekyll.com/getstarted/#install-steps-hard) that include either using GitHub Pages with remote themes, or using Ruby gems. They provide you with more control, but are only intended for advanced users.

> Note: Beautiful Jekyll was primarily designed to be used as a GitHub theme, so you will not get any support if you use this theme via Ruby gems. 

# Plans

Beautiful Jekyll is, and always will be, free. But if you want to remove the Beautiful Jekyll ad from your website, use a Dark Mode skin, access office hours, or simply support the development efforts, [check out the different plans](https://beautifuljekyll.com/plans).

# Add your own content

To add pages to your site, you can either write a markdown file (`.md`) or you can write an HTML file. It's much easier to write markdown than HTML, so that's the recommended approach ([here's a great tutorial](https://markdowntutorial.com/) if you need to learn markdown in 5 minutes).

To see an example of a markdown file, click on any file that ends in `.md`, for example [`aboutme.md`](./aboutme.md). On that page you can see some nicely formatted text (there's a word in bold, a link, a few bullet points), and if you click on the pencil icon to edit the file, you'll see the markdown code that generated the pretty text. Very easy! 

In contrast, look at [`tags.html`](./tags.html). That's how your write HTML - not as pretty. So stick with markdown if you don't know HTML.

Any markdown or HTML file that you create will be available on your website under `https://<yourusername>.github.io/<pagename>`. For example, if you create a file `about.md` (or `about.html`) then it'll exist at `https://<yourusername>.github.io/about`.

Files you create inside the [`_posts`](./_posts) directory will be treated as blog entries. You can look at the existing files there to get an idea of how to write blog posts. Note the format of the blog post files - they must follow the naming convention of `YEAR-MONTH-DAY-title.md`. After you successfully add your own post, you can delete the existing files inside [`_posts`](./_posts) to remove the sample posts, as those are just demo posts to help you learn.

# Customizing parameters for each page

**One last important thing**: In order to have your new pages use this template and not just be plain HTML pages, **you must add [YAML front matter](https://jekyllrb.com/docs/front-matter/) to the top of each page**:


```
---
---
```

This is where you'll be able to give each page some extra parameters (such as a title, a subtitle, an image, etc - [below is a list of all parameters](#supported-parameters)). Add any parameters you want between these two dashed lines, for example:

```
---
title: Contact me
subtitle: Here you'll find all the ways to get in touch with me
---
```

If you don't want to use any parameters on a page, you still need to use the two dashed lines. If you don't, then your file will be shown as-is without the Beautiful Jekyll template.

You can look at the top of [`aboutme.md`](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/aboutme.md) as an example.

**Important takeaway: ALWAYS add the YAML front matter, which is two lines of three dashes, to EVERY page. If you have any parameters, they go between the two lines.**

# Supported parameters

Below is a list of the parameters that Beautiful Jekyll supports (any of these can be added to the YAML front matter of any page). Remember to also look in the `_config.yml` file to see additional site-wide settings. If there's a parameter that you want to apply to the entire site instead of one specific page, check out [this FAQ answer](https://beautifuljekyll.com/faq/#default-params).

## Main parameters

These are the basic YAML parameters that you are most likely to use on most pages.

Parameter   | Description
----------- | -----------
title       | Page or blog post title
subtitle    | Short description of page or blog post that goes under the title
tags        | List of tags to categorize the post. Separate the tags with commas and place them inside square brackets. Example: `[personal, analysis, finance]`
cover-img   | Include a large full-width image at the top of the page. You can either provide the path to a single image (eg. `"/path/to/img"`) , or a list of images to cycle through (eg. `["/path/img1", "/path/img2"]`). If you want to add a caption to an image, then you must use the list notation (use `[]` even if you have only one image), and each image should be provided as `"/path/to/img" : "Caption of image"`.
thumbnail-img | For blog posts, if you want to add a thumbnail that will show up in the feed, use `thumbnail-img: /path/to/image`. If no thumbnail is provided, then `cover-img` will be used as the thumbnail. You can use `thumbnail-img: ""` to disable a thumbnail.
comments    | If you want do add comments to a specific page, use `comments: true`. Comments only work if you enable one of the comments providers (Facebook, disqus, staticman, utterances, giscus, CommentBox) in `_config.yml` file. Comments are automatically enabled on blog posts but not on other pages; to turn comments off for a specific post, use `comments: false`.
mathjax     | If you want to use LaTeX formulas, you need to enable MathJax. Note that in MathJax you need to use `$$` and `\\(` to start and end expressions

## Parameters for SEO and social media sharing

These parameters let you control what information shows up when a page is shown in a search engine (such as Google) or gets shared on social media (such as Twitter/Facebook).

Parameter   | Description
----------- | -----------
share-title | A title for the page. If not provided, then `title` will be used, and if that's missing then the site title (from `_config.yml`) is used.
share-description | A brief description of the page. If not provided, then `subtitle` will be used, and if that's missing then an excerpt from the page content is used.
share-img   | The image to show. If not provided, then `cover-img` or `thumbnail-img` will be used if one of them is provided.

## Less commonly used parameters

These are parameters that you may not use often, but can come in handy sometimes.

Parameter   | Description
----------- | -----------
author      | Specify the author of a blog post (useful if a website has multiple authors).
readtime    | If you want a post to show how many minutes it will take to read it, use `readtime: true`.
show-avatar | If you have an avatar configured in the `_config.yml` but you want to turn it off on a specific page, use `show-avatar: false`.
social-share | By default, every blog post has buttons to share the page on social media. If you want to turn this feature off, use `social-share: false`.
nav-short   | By default, the navigation bar gets shorter after scrolling down the page. If you want the navigation bar to always be short on a certain page, use `nav-short: true`
gh-repo   | If you want to show GitHub buttons at the top of a post, this sets the GitHub repo name (eg. `daattali/beautiful-jekyll`). You must also use the `gh-badge` parameter to specify what buttons to show.
gh-badge  | Select which GitHub buttons to display. Available options are: [star, watch, fork, follow]. You must also use the `gh-repo` parameter to specify the GitHub repo.
last-updated | If you want to show that a blog post was updated after it was originally released, you can specify an "Updated on" date.
layout      | What type of page this is (default is `post` for blog posts and `page` for other pages). See _Page types_ section below for more information.

## Advanced parameters

These are advanced parameters that are only useful for people who need very fine control over their website.

Parameter   | Description
----------- | -----------
footer-extra | If you want to include extra content below the social media icons in the footer, create an HTML file in the `_includes/` folder (for example `_includes/myinfo.html`) and set `footer-extra` to the name of the file (for example `footer-extra: myinfo.html`). Accepts a single file or a list of files.
before-content | Similar to `footer-extra`, but used for including HTML before the main content of the page (below the title).
after-content | Similar to `footer-extra`, but used for including HTML after the main content of the page (above the footer).
head-extra   | Similar to `footer-extra`, but used if you have any HTML code that needs to be included in the `<head>` tag of the page.
language    | HTML language code to be set on the page's &lt;html&gt; element.
full-width  | By default, page content is constrained to a standard width. Use `full-width: true` to allow the content to span the entire width of the window.
js          | List of local JavaScript files to include in the page (eg. `/assets/js/mypage.js`)
ext-js      | List of external JavaScript files to include in the page (eg. `//cdnjs.cloudflare.com/ajax/libs/underscore.js/1.8.2/underscore-min.js`). External JavaScript files that support [Subresource Integrity (SRI)](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) can be specified using the `href` and `sri` parameters eg.<br/>`href: "//code.jquery.com/jquery-3.1.1.min.js"`<br/>`sri: "sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8="`
css         | List of local CSS files to include in the page
ext-css      | List of external CSS files to include in the page. External CSS files using SRI (see `ext-js` parameter) are also supported.

## Page types

- **post** - To write a blog post, add a markdown or HTML file in the `_posts` folder. As long as you give it YAML front matter (the two lines of three dashes), it will automatically be rendered like a blog post. Look at the existing blog post files to see examples of how to use YAML parameters in blog posts.
- **page** - Any page outside the `_posts` folder that uses YAML front matter will have a very similar style to blog posts.
- **home** - The home layout is meant to act as the homepage of your blog posts - it will display all your blog posts, sorted from newest to oldest. A file using the `home` layout must be named `index.html` (not `index.md` or anything else!).
- **minimal** - If you want to create a page with minimal styling (ie. without the bulky navigation bar and footer), assign `layout: minimal` to the YAML front matter.
- If you want to completely bypass the template engine and just write your own HTML page, simply omit the YAML front matter. Only do this if you know how to write HTML!

# Featured users (success stories!)

Visit the [Official website](http://beautifuljekyll.com/examples) to see sample websites using Beautiful Jekyll.

If you'd like to showcase yourself and join this list, [upgrading to the Individual plan](https://github.com/sponsors/daattali/sponsorships?&tier_id=7362) will give you that publicity plus some other rewards!

# Next steps

Congratulations on making it this far! You now have all the tools to easily build a beautiful website for free. 

- After you get comfortable with the basics of writing in markdown, I suggest taking a look at this [sample post](https://beautifuljekyll.com/2020-02-28-sample-markdown/) and [the code that created it](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/_posts/2020-02-28-sample-markdown.md) to learn some more advanced tips about markdown.

- I **highly recommend** going over the [*Frequently Asked Questions*](https://beautifuljekyll.com/faq/) to find out answers to questions you may not even know you have. Every few months I suggest checking the [*What's New?*](https://beautifuljekyll.com/updates/) page to see if there are new features, and learn [how to update your site to the newest version](https://beautifuljekyll.com/faq/#updating) when it's time.

- You can also check out the [advanced installation methods](https://beautifuljekyll.com/getstarted/#install-steps-hard) that give you a little more control but are harder to use. Keep in mind that Beautiful Jekyll was primarily designed to be used as a GitHub theme, so you will not get any support if you choose one of the Ruby installation methods. 

- Remember that Beautiful Jekyll is built on top of Jekyll. This means that reading through the [Jekyll documentation](https://jekyllrb.com/) will introduce you to many more features that you might find useful!

# Getting help

Visit the [FAQ page](https://beautifuljekyll.com/faq) for answers to commonly asked questions.

**If you choose to [become a sponsor](https://beautifuljekyll.com/plans/), you'll have access to my [office hours](https://beautifuljekyll.com/officehours/) where you can ask for help.** You can also use the [Discussions](https://github.com/daattali/beautiful-jekyll/discussions) area to try and get help from the community.

Beautiful Jekyll is used by 50,000+ people with wildly varying degrees of web skills, so it's impossible to answer all the questions that may arise. For any question that's not specifically related to Beautiful Jekyll and is more about Jekyll or web development in general, the answer can often be found on Google, in the [Jekyll documentation](https://jekyllrb.com/), or on the [Jekyll support forum](https://talk.jekyllrb.com/).

# Contributions

Thank you to [all past contributors](https://github.com/daattali/beautiful-jekyll/graphs/contributors). If you find any problems or would like to contribute in any way, feel free to create a pull request/open an issue/send me a message.

You can also contribute by becoming an [official sponsor](https://github.com/sponsors/daattali/sponsorships?tier_id=39856) to help keep Beautiful Jekyll well-maintained!

# Credits

This template was not made *entirely* from scratch. I'd like to give special thanks to [Jekyll Now](https://github.com/barryclark/jekyll-now) and [Bootstrap Clean Blog](https://github.com/IronSummitMedia/startbootstrap-clean-blog), from whom I've taken several ideas initially.

I'd also like to thank [Dr. Jekyll's Themes](https://drjekyllthemes.github.io/), [Jekyll Themes](http://jekyllthemes.org/), and another [Jekyll Themes](http://jekyllrc.github.io/jekyllthemes/) for featuring Beautiful Jekyll in their Jekyll theme directories.





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


Here’s a clear comparison of AddScoped, AddSingleton, and AddTransient in .NET Core Dependency Injection:
---
1. AddSingleton<br>
•	Lifetime: Only one instance is created and shared for the entire application lifetime.<br>
•	When to use: For stateless services or services that maintain shared state/caches/configuration.<br>
•	Example:
	builder.Services.AddSingleton<IMyService, MyService>();
	
	Request 1 - Service1: 9f2a0c0b-4c92-41d7-8a11-ea7a3c8cb1f9<br>
	Request 1 - Service2: 9f2a0c0b-4c92-41d7-8a11-ea7a3c8cb1f9<br>

	Request 2 - Service1: 9f2a0c0b-4c92-41d7-8a11-ea7a3c8cb1f9<br>
	Request 2 - Service2: 9f2a0c0b-4c92-41d7-8a11-ea7a3c8cb1f9<br>

	
2. AddScoped<br>
•	Lifetime: One instance is created per HTTP request (scope). The same instance is used throughout a single request, but a new one is created for each new request.<br>
•	When to use: For services that should be unique per request, such as database contexts (e.g., Entity Framework’s DbContext).<br>
•	Example:
	builder.Services.AddScoped<IMyService, MyService>();
	
	Request 1 - Service1: c1f105dc-b842-4b62-99a4-96c5024e4f2d<br>
	Request 1 - Service2: c1f105dc-b842-4b62-99a4-96c5024e4f2d<br>

	Request 2 - Service1: 82c764b5-d893-4cfb-ae80-ec82c5f72b12<br>
	Request 2 - Service2: 82c764b5-d893-4cfb-ae80-ec82c5f72b12<br>

	
3. AddTransient<br>
•	Lifetime: A new instance is created every time the service is requested.<br>
•	When to use: For lightweight, stateless services or operations that do not need to maintain state between calls.<br>
•	Example:
	builder.Services.AddTransient<IMyService, MyService>();
	
	Request 1 - Service1: f6b10d21-9644-4e82-b1c0-5ff47b66d9a6<br>
	Request 1 - Service2: 7383a5a2-6c77-465a-9b6b-9c89dc85e7a1<br>

	Request 2 - Service1: 3bdf2b3b-e204-4c39-b0f1-32c99f72c689<br>
	Request 2 - Service2: b1045fe2-0d55-4a69-81c5-e81aef6d4d4b<br>


| Method         | Lifetime             | Use Case Example                |
| -------------- | -------------------- | ------------------------------- |
| `AddSingleton` | Application-wide     | Logging, configuration, caching |
| `AddScoped`    | Per HTTP request     | Database context, unit of work  |
| `AddTransient` | Every injection/call | Utility/helper services         |

Tip:
•	Use AddSingleton for shared, thread-safe services.
•	Use AddScoped for services that should be unique per request.
•	Use AddTransient for lightweight, stateless, and short-lived services.	


public interface IMyService
{
    Guid GetOperationId();
}

public class MyService : IMyService
{
    private Guid _operationId;

    public MyService()
    {
        _operationId = Guid.NewGuid();
    }

    public Guid GetOperationId() => _operationId;
}


Major OOP Concepts
1.	Encapsulation
•	Bundling data and methods that operate on that data within a class.
•	Access modifiers (public, private, protected, internal).
2.	Abstraction
•	Hiding complex implementation details and showing only the necessary features.
•	Achieved using abstract classes and interfaces.
3.	Inheritance
•	Mechanism to derive a new class from an existing class.
•	Supports code reuse and hierarchical relationships.
4.	Polymorphism
•	Ability to take many forms.
•	Compile-time (method overloading) and runtime (method overriding via virtual/override).
 
Additional OOP Topics
•	Classes and Objects
•	Constructors and Destructors
•	Static vs Instance Members
•	Sealed Classes
•	Partial Classes
•	Abstract Classes vs Interfaces
•	Access Modifiers
•	Properties, Indexers, and Events
•	Operator Overloading
•	Exception Handling in OOP
•	Design Patterns (Singleton, Factory, etc.)
 
Common OOP Interview Questions
1.	What is the difference between abstraction and encapsulation?
2.	How does inheritance work in C#? Can you inherit from multiple classes?
3.	What is polymorphism? Explain with examples.
4.	When would you use an abstract class vs an interface?
5.	What are access modifiers and why are they important?
6.	How does method overloading differ from method overriding?
7.	What is a sealed class and when would you use it?
8.	Explain the concept of constructor chaining.
9.	What is the purpose of the base and this keywords?
10.	How do you implement encapsulation in C#?


Certainly! Here are more OOP and .NET Core interview/practice questions to help deepen your understanding:
 
OOP Questions
1.	What is the difference between a class and an object?
2.	Explain the concept of constructor overloading.
3.	What is method hiding? How is it different from method overriding?
4.	What is an interface and how is it different from an abstract class?
5.	How does C# support multiple inheritance?
6.	What is the purpose of the sealed keyword in C#?
7.	What is the difference between static and instance members?
8.	How do you implement encapsulation in C#?
9.	What is the use of the base keyword?
10.	What is operator overloading? Give an example.
 
.NET Core Questions
1.	What is the difference between IActionResult and ActionResult<T> in ASP.NET Core?
2.	How do you implement exception handling in ASP.NET Core?
3.	What is middleware? How do you create custom middleware?
4.	How does model validation work in ASP.NET Core?
5.	What is dependency injection and how is it configured in .NET Core?
6.	How do you use configuration and options pattern in .NET Core?
7.	What is the difference between synchronous and asynchronous programming in .NET Core?
8.	How do you secure an ASP.NET Core Web API?
9.	What is the purpose of app.UseEndpoints()?
10.	How do you implement logging in .NET Core?
 
 
Basic Concepts
1.	What is MVC? Explain its components.
2.	What is the role of a Controller in MVC?
3.	How does routing work in ASP.NET Core MVC?
4.	What is a ViewModel and why is it used?
5.	What is the difference between ViewData, ViewBag, and TempData?
6.	How do you pass data from a Controller to a View?
7.	What is model binding in MVC?
8.	How do you perform validation in MVC?
9.	What are Action Results? Name a few types.
10.	What is the purpose of filters in MVC?
---
Intermediate/Advanced
1.	How do you implement custom filters in ASP.NET Core MVC?
2.	What is dependency injection and how is it used in controllers?
3.	How do you handle exceptions in MVC applications?
4.	What is Partial View? When would you use it?
5.	What is the difference between a Partial View and a Layout View?
6.	How do you implement authentication and authorization in MVC?
7.	What is Razor syntax?
8.	How do you use Tag Helpers in ASP.NET Core MVC?
9.	What is the difference between synchronous and asynchronous action methods?
10.	How do you return JSON data from a controller?

    Basic Questions
1.	What is a Web API?
2.	What is the difference between Web API and MVC?
3.	How do you create a simple Web API in ASP.NET Core?
4.	What are HTTP verbs and how are they used in Web API?
5.	How do you route requests to controller actions in Web API?
6.	What is model binding in Web API?
7.	How do you return different HTTP status codes from an API action?
8.	What is the purpose of IActionResult and ActionResult<T>?
9.	How do you enable CORS in ASP.NET Core Web API?
10.	How do you document a Web API (e.g., using Swagger)?
---
Intermediate/Advanced Questions
1.	How do you implement authentication and authorization in Web API?
2.	What is dependency injection and how is it used in Web API controllers?
3.	How do you handle exceptions and errors in Web API?
4.	What is versioning in Web API and how do you implement it?
5.	How do you secure sensitive data in Web API responses?
6.	What is throttling and how can you implement rate limiting in Web API?
7.	How do you test a Web API?
8.	What is the difference between synchronous and asynchronous API actions?
9.	How do you use filters (like action filters, exception filters) in Web API?
10.	How do you implement custom middleware for logging or error handling in Web API?

    Basic Questions
1.	What is WCF?
2.	What are the main components of WCF?
3.	What is an endpoint in WCF?
4.	Explain the ABCs of WCF (Address, Binding, Contract).
5.	What are bindings in WCF? Name a few types.
6.	What is a service contract, data contract, and operation contract?
7.	How do you host a WCF service?
8.	What is the difference between WCF and Web API?
9.	What is the purpose of the ServiceBehavior attribute?
10.	How do you consume a WCF service in a client application?
---
Intermediate/Advanced Questions
1.	What is the difference between BasicHttpBinding and WSHttpBinding?
2.	How do you implement security in WCF?
3.	What is message contract in WCF?
4.	What is the purpose of the InstanceContextMode and ConcurrencyMode?
5.	How do you handle transactions in WCF?
6.	What is throttling in WCF and how do you configure it?
7.	How do you enable and use reliable messaging in WCF?
8.	What is the difference between PerCall, PerSession, and Single instance modes?
9.	How do you implement error handling and fault contracts in WCF?
10.	What are the different ways to host a WCF service (IIS, WAS, Self-hosting, Windows Service)?

    Basic Questions
1.	What is Angular and how is it different from AngularJS?
2.	What are components in Angular?
3.	What is a module in Angular?
4.	What is data binding? Name the types of data binding in Angular.
5.	What are directives? Name the types of directives in Angular.
6.	What is a service in Angular and why is it used?
7.	How do you create and use a service in Angular?
8.	What is dependency injection in Angular?
9.	What is routing in Angular?
10.	How do you pass data between components?
---
Intermediate/Advanced Questions
1.	What is the difference between ngOnInit and constructor in a component?
2.	What are lifecycle hooks in Angular?
3.	What is an Observable? How is it used in Angular?
4.	How do you handle HTTP requests in Angular?
5.	What is the purpose of the HttpClientModule?
6.	What is lazy loading in Angular?
7.	What is a guard in Angular routing? Name different types of guards.
8.	How do you implement form validation in Angular?
9.	What is the difference between template-driven and reactive forms?
10.	What is Change Detection in Angular? How does it work?

    Basic Questions
1.	What is SQL Server?
2.	What are the different types of SQL Server databases?
3.	What is a primary key and a foreign key?
4.	What is normalization? Explain its types.
5.	What is a JOIN? Name different types of JOINs in SQL Server.
6.	What is the difference between WHERE and HAVING clauses?
7.	What is an index? Why is it used?
8.	What is a stored procedure?
9.	What is a view?
10.	What is a trigger?
---
Intermediate/Advanced Questions
1.	What is the difference between clustered and non-clustered indexes?
2.	How do you optimize a slow-running query?
3.	What is a transaction? Explain ACID properties.
4.	What is deadlock? How can you prevent or resolve it?
5.	What are the differences between DELETE, TRUNCATE, and DROP?
6.	How do you implement security in SQL Server?
7.	What is a CTE (Common Table Expression)?
8.	What is the difference between a function and a stored procedure?
9.	How do you perform backup and restore operations in SQL Server?
10.	What is SQL Server Agent?

What is CI/CD?
•	Continuous Integration (CI):
Developers frequently merge code changes into a shared repository. Each merge triggers an automated build and test process, ensuring code quality and early bug detection.
•	Continuous Deployment/Delivery (CD):
After CI, code is automatically (deployment) or manually (delivery) released to production or staging environments. This automates the release process and reduces manual errors.
---
Typical CI/CD Pipeline Steps
1.	Source Control:
Code is pushed to a repository (e.g., GitHub, Azure Repos).
2.	Build:
The application is built (e.g., using dotnet build for .NET).
3.	Test:
Automated tests are run (e.g., dotnet test).
4.	Publish/Package:
The build output is packaged for deployment.
5.	Deploy:
The package is deployed to a server, cloud, or container.
6.	Monitor:
Application health and logs are monitored post-deployment.

1. C# Basics
•	Data types, variables, constants
•	Operators and expressions
•	Control statements (if, switch, loops)
•	Exception handling (try-catch-finally)
•	Namespaces and assemblies
---
2. Object-Oriented Programming (OOP)
•	Classes and objects
•	Inheritance, polymorphism, encapsulation, abstraction
•	Interfaces vs. abstract classes
•	Constructors, destructors, static members
•	Access modifiers
---
3. Collections & Generics
•	Arrays, Lists, Dictionaries, HashSet, Stack, Queue
•	Generic types and methods
•	LINQ basics
---
4. Delegates, Events, and Lambdas
•	Delegates and multicast delegates
•	Events and event handling
•	Anonymous methods, lambda expressions
•	Func, Action, Predicate
---
5. LINQ (Language Integrated Query)
•	LINQ to Objects, LINQ to Entities
•	Query syntax vs. method syntax
•	Filtering, projection, grouping, joining
---
6. Asynchronous Programming
•	async and await keywords
•	Task Parallel Library (TPL)
•	Threading basics
---
7. Memory Management & Garbage Collection
•	Value types vs. reference types
•	Stack vs. heap
•	IDisposable and using statement
•	Finalizers
---
8. File I/O and Serialization
•	Reading/writing files (File, StreamReader, StreamWriter)
•	JSON/XML serialization and deserialization
---
9. Attributes & Reflection
•	Custom attributes
•	Using reflection to inspect types and members
---
10. Dependency Injection & Design Patterns
•	Constructor injection, property injection
•	Common patterns: Singleton, Factory, Repository
---
11. ASP.NET Core (if applicable)
•	Middleware, controllers, routing
•	Model binding, validation
•	Dependency injection in ASP.NET Core
•	RESTful API basics
---
12. Unit Testing
•	Writing unit tests (xUnit, NUnit, MSTest)
•	Mocking dependencies
---
Tip: Interviewers often focus on OOP, collections, LINQ, async/await, and real-world scenarios (like API design or error handling).

📘 .NET Core Web API Syllabus
Module 1: Introduction to .NET Core and RESTful APIs
		  Overview of .NET Core and .NET 6/7/8
		  What is a Web API?
		  REST principles (GET, POST, PUT, DELETE, PATCH)
		  Setting up the development environment (Visual Studio / VS Code)
		  Creating your first ASP.NET Core Web API project

Module 2: Controllers & Routing
		  Creating API Controllers
		  Attribute Routing vs. Convention-Based Routing
		  Route parameters and query strings
		  IActionResult vs ActionResult<T>

Module 3: Model Binding and Validation
		  Creating request/response models (DTOs)
		  Model binding from route, query, body
		  Data annotations for validation
		  Custom validation attributes

Module 4: Dependency Injection
		  What is DI?
		  Registering and injecting services
		  Scoped, Singleton, and Transient lifetimes

Module 5: Entity Framework Core Integration
		  Introduction to EF Core
		  Creating the DbContext and entities
		  Migrations and database updates
		  CRUD operations using EF Core
		  Using LINQ with EF Core

Module 6: Middleware & Pipeline
		  ASP.NET Core Middleware pipeline
		  Built-in middleware (e.g., CORS, static files, exception handling)
		  Creating custom middleware

Module 7: Authentication & Authorization
		  Authentication vs. Authorization
		  Using JWT (JSON Web Tokens)
		  ASP.NET Core Identity basics
		  Role-based and Policy-based authorization

Module 8: Advanced Topics
		  Logging (using ILogger, Serilog)
		  Exception handling and global error responses
		  Versioning your API
		  Caching (in-memory and response caching)

Module 9: Testing Web APIs
		  Unit testing controllers and services
		  Integration testing with TestServer
		  Mocking dependencies with Moq

Module 10: API Documentation & Tools
		   Swagger/OpenAPI setup
		   Customizing Swagger UI
		   Postman / REST Client for testing

Module 11: Deployment & Hosting
		   Hosting on IIS, Kestrel, or Docker
		   Publishing to Azure / AWS / Linux
		   AppSettings & Environment configuration
		   
		   
		   
Great! Since you're working with a stack that includes ASP.NET, MVC, WCF, Web API, and .NET Core, you’ll benefit from a suite of tools that improve developer productivity, code quality, collaboration, documentation, and testing.

Here's a categorized breakdown of the best tools for each area:

✅ 1. Documentation
Tool	Use Case	Notes
Swashbuckle / NSwag	API documentation (Swagger UI) for ASP.NET Core / Web API	Auto-generates Swagger/OpenAPI docs //https://petstore.swagger.io/?utm_source=chatgpt.com#/pet/findPetsByTags
Sandcastle	XML documentation generator (legacy)	Good for full .NET Framework, not Core
DocFX	Generates documentation from source code and markdown	Open-source, used by Microsoft

✅ 2. Code Review / Collaboration
Tool	Use Case	Notes
GitHub / GitLab / Azure DevOps	Code repository with pull request reviews	Choose based on your CI/CD platform
SonarQube	Static code analysis & code quality reports	Works with .NET and .NET Core
FxCop / Roslyn Analyzers	Enforce coding standards	Integrated into Visual Studio
ReSharper	Advanced code analysis and refactoring	Increases developer productivity in Visual Studio

✅ 3. Unit Testing & Test Coverage
Tool	Use Case	Notes
xUnit / NUnit / MSTest	Unit testing frameworks	xUnit is preferred for .NET Core
Moq / NSubstitute	Mocking dependencies in tests	Moq is widely used
coverlet	Code coverage for .NET Core	Integrates with xUnit and works with Visual Studio
ReportGenerator	Generates HTML code coverage reports	Works well with Coverlet and Azure DevOps

✅ 4. CI/CD and Build Automation
Tool	Use Case	Notes
Azure DevOps Pipelines	CI/CD for .NET apps	Full Microsoft ecosystem support
GitHub Actions	Lightweight CI/CD	Great for open-source and GitHub-hosted projects
Jenkins	General-purpose CI/CD	Needs more setup for .NET
Cake / Nuke	Build automation using C#	Better than MSBuild scripts for complex automation

✅ 5. Configuration Management
Tool	Use Case	Notes
User Secrets (ASP.NET Core)	Store dev secrets securely	Use for local dev only
Azure App Configuration	Centralized configuration	Ideal for cloud-hosted apps
Environment Variables + appsettings.json	Standard config pattern	Use appsettings.Development.json for local dev

✅ 6. Debugging & Performance
Tool	Use Case	Notes
Visual Studio Profiler	Performance analysis	Integrated in Enterprise edition
dotTrace	Advanced performance profiler	JetBrains tool, integrates with ReSharper
Application Insights	Telemetry and diagnostics	Great for ASP.NET Core + Azure

✅ 7. Dependency Management
Tool	Use Case	Notes
NuGet	Package management	Built-in to .NET ecosystem
Dependabot (GitHub)	Auto-updates dependencies	Helps keep your stack secure

✅ 8. UI Testing (if applicable)
Tool	Use Case	Notes
Selenium / Playwright	End-to-end testing for MVC apps	Playwright is more modern and faster
PuppeteerSharp	Headless browser testing	C# wrapper for headless Chrome

🧠 Bonus Productivity Tools
Visual Studio Live Share: Remote collaboration / pair programming

Postman / REST Client in VS Code: Testing APIs quickly

DevExpress / Telerik: UI controls for ASP.NET/MVC

Would you like a recommended toolchain setup based on team size (e.g., startup vs enterprise) or cloud vs on-prem deployment?		   
