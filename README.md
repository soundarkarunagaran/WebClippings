# Web Clippings

Clip&middot;ping: _noun_ Something cut off or out, especially an item clipped from a newspaper or magazine.

Following is personal collection of mostly software-related articles and downloads that I have found useful and bookmarked for future reference:

## [Cleaning Up After Migrating From Hg to Git](http://christoph.ruegg.name/blog/cleaning-up-after-migrating-from-hg-to-git.html)

> There is a lot of guidance out there on how to migrate from Mercurial to Git, but they often leave you with a repository in a bad state. Even more so if it originally was a subversion repository, then migrated to Mercurial and now finally to Git.

Tags: `git`, `hg`

Tue Mar 01 18:42:10 2016 +0100

## [Further Down the Rabbit Hole: PowerShell Modules and Encapsulation](https://www.simple-talk.com/dotnet/.net-tools/further-down-the-rabbit-hole-powershell-modules-and-encapsulation/)

> Modules allow you to use standard libraries that extend PowerShell&rsquo;s functionality. They are easier to use than to create, but if you get the hang of creating them, your code will be more easily-maintained and re-usable. Let Michael Sorens once more be your guide through PowerShell&rsquo;s &lsquo;Alice in Wonderland&rsquo; world.

Tags: `psh`

Tue Feb 02 18:34:12 2016 +0100

## [SQL Server and Node.js, BFFs For Life](http://nerdventure.io/sql-server-and-node-js/)

> Recently, with the help of other reference implementations and documents, I was able to add NTLM authentication support to what I consider the best SQL lib for Node.js.

Tags: `node`, `mssql`, `ntlm`

Mon Feb 01 11:59:01 2016 +0100

## [ServiceWorker: Revolution of the Web Platform](https://ponyfoo.com/articles/serviceworker-revolution)

> While not the most amusingly named feature of the web platform, everything seems to point at ServiceWorker being the **most significant addition** to the web platform since the introduction of *AJAX* – over 10 years ago. Not to be confused with WebWorker (*used to offload intense compute operations onto another execution thread*), ServiceWorker allows you to intercept (*and hijack*) network requests originating from your site before they’re even dispatched. This article explores how it works, what it means and what it enables, and how you can implement it by following a case study.

Tags: `web`

Sun Jan 31 21:26:43 2016 +0100

## [Goodbye Child Actions, Hello View Components](http://www.davepaquette.com/archive/2016/01/02/goodbye-child-actions-hello-view-components.aspx)

> In previous versions of MVC, we used [Child Actions](http://haacked.com/archive/2009/11/18/aspnetmvc2-render-action.aspx/) to build reusable components / widgets that consisted of both Razor markup and some backend logic. The backend logic was implemented as a controller action and typically marked with a `[ChildActionOnly]` attribute. Child actions are extremely useful but as some have pointed out, it is easy to [shoot yourself in the foot](http://www.khalidabuhakmeh.com/obscure-bugs-asp-net-mvc-child-actions).

> **Child Actions do not exist in MVC 6.** Instead, we are encouraged to use the new View Component feature to support this use case. Conceptually, view components are a lot like child actions but they are a lighter weight and no longer involve the lifecycle and pipeline related to a controller. Before we get into the differences, let’s take a look at a simple example.

Tags: `aspnet`, `mvc` 

Fri Jan 29 13:40:23 2016 +0100

## [How to Take an Asp.Net MVC Web Site Down for Maintenance](https://www.simple-talk.com/dotnet/asp.net/how-to-take-an-asp.net-mvc-web-site-down-for-maintenance/)

> Keeping a customer facing web site up and performing well is a challenge, especially when you are still adding new features. While providing an &ldquo;always on&rdquo; experience for users is preferred there are times when it is easier to take the site &ldquo;down for maintenance&rdquo; and fix those things that are just too difficult and costly to do with the site up. Jon Smith describes his solution to a controlled &ldquo;down for maintenance&rdquo; approach for ASP.NET MVC sites.

Tags: `aspnet`, `mvc` 

Fri Jan 29 13:38:51 2016 +0100

## [Announcing NuGet 3.1 with Support for Universal Windows Platform](http://blog.nuget.org/20150729/Introducing-nuget-uwp.html)

> Today the NuGet team in collaboration with several other teams at Microsoft is happy to announce the release of a new version of the NuGet clients supporting the Universal Windows Platform and the new Portable class libraries. The NuGet tools are available through Tools&rarr;Extensions and Updates&rarr;Update tab in Visual Studio 2015 as well as from our [GitHub repository](https://github.com/nuget/home/releases). Additionally, we have released a new version of the NuGet command-line tool that you can download from [NuGet.org](http://dist.nuget.org/win-x86-commandline/v3.1.0-beta/nuget.exe).

> In this post, we will review the new capabilities that package authors can use and the process that windows programmers need to follow in order to use NuGet with their projects.

Tags: `nuget`, `uwp`

Fri Jan 29 13:36:01 2016 +0100

## [Why write Python in Visual Studio?](http://blogs.msdn.com/b/visualstudio/archive/2015/08/03/why-write-python-in-visual-studio.aspx)

Recently, [Visual Studio 2015](http://www.microsoft.com/click/services/Redirect2.ashx?CR_CC=200661214) was released with support for Python. [Python Tools for Visual Studio](https://github.com/Microsoft/PTVS) (PTVS) are available to help throughout Visual Studio in all the places you’d expect, from editing and IntelliSense, to debugging, profiling, and publishing to Azure. You can find all the details and some [video walkthroughs, documentation, and other resources](https://aka.ms/ptvs) on visualstudio.com, and the post announcing [Python Tools 2.1](http://blogs.msdn.com/b/visualstudio/archive/2014/10/15/python-tools-2-1-for-visual-studio.aspx) and [Python Tools 2.2 beta](http://blogs.msdn.com/b/visualstudio/archive/2015/03/16/python-tools-for-visual-studio-2-2-beta-released.aspx). In this post I want to talk about some of the reasons to consider using Visual Studio next time you are working in Python.

Fri Jan 29 13:32:21 2016 +0100

Tags: `vs`, `python`

## [The .NET Framework 4.5 includes new garbage collector enhancements for client and server apps](http://blogs.msdn.com/b/dotnet/archive/2012/07/20/the-net-framework-4-5-includes-new-garbage-collector-enhancements-for-client-and-server-apps.aspx)

> In this post, we will look at how the CLR garbage collector (GC) has been changed in the .NET Framework 4.5 to meet the needs of large client and server apps. These improvements are in response to requests from developers who use the .NET Framework to build large-scale commercial apps. Some of these customers have already reported significant wins after deploying the .NET Framework 4.5 (currently available as an RC release) into production.

Tags: `dotnet`, `gc`

Fri Jan 29 13:29:19 2016 +0100

## [The Tipping Point Query Answers](http://www.sqlskills.com/blogs/kimberly/the-tipping-point-query-answers/)

> **What is the tipping point?** It's the point where the number of rows returned is "no longer selective enough". SQL Server chooses NOT to use the nonclustered index to look up the corresponding data rows and instead performs a table scan.

Tags: `mssql`, `db`, `unread`

Fri Jan 29 13:26:34 2016 +0100

## [R Programming Language - Introduction to R for C# Programmers](https://msdn.microsoft.com/en-us/magazine/Mt238409.aspx)

> The R language is used by data scientists and programmers for statistical computing. In part because of the increasing amounts of data collected by software systems, and the need to analyze that data, R is one of the fastest-growing technologies among my colleagues who use C#. A familiarity with R can be a valuable addition to your technical skill set.

Tags: `r`, `unread`

Fri Jan 29 13:22:06 2016 +0100

## [Recommendations and guidelines for the &ldquo;max degree of parallelism&rdquo; configuration option in SQL Server](https://support.microsoft.com/en-us/kb/2806535)

> The Microsoft SQL Server **max degree of parallelism** (`MAXDOP`) configuration option controls the number of processors that are used for the execution of a query in a parallel plan. This option determines the computing and thread resources that are used for the query plan operators that perform the work in parallel. Depending on whether SQL Server is set up on a symmetric multiprocessing (SMP) computer, a non-uniform memory access (NUMA) computer, or hyperthreading-enabled processors, you have to configure the **max degree of parallelism** option appropriately. This article discusses the general guidelines that you can use to configure the **max degree of parallelism** option for SQL Server when you use the `sp_configure` system stored procedure. 

Tags: `mssql`, `mskb`, `admin`

Fri Jan 29 13:16:34 2016 +0100
