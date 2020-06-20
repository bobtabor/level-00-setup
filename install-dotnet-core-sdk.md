The .NET core SDK contains all of the files you'll need to write, debug, compile and run your C# programs.  .NET Core is the new version of dotnet.  The previous version was called the .NET framework.  There are a few significant changes -- it was almost a complete re-write.  We'll talk about the difference between .NET Core and .NET Framework in another course, but for our purposes in this course, it's important that you download and install the newer .NET Core.

Start by searching for "dotnet core sdk download" in a search engine.  You'll want to choose a result that takes you to a Microsoft owned domain.  You should see options that look similar to this page.  It's likely the page design will change over time, so read carefully.

You want .NET Core, not the .NET Framework.

Also important -- you want to download and install the .NET Core SDK, or Software Development Kit.  The SDK is for software developers like you.  The .NET Core Runtime is for people who will use your completed, compiled application.

Finally, you want to download and install the latest supported version.  As you can see, as I'm recording this video in the summer of 2020, there's an upcoming version of .NET Core in preview.  .NET Core is in a yearly update cadence, meaning that every year a new version of .NET Core will be released.  Usually, new versions mean **additional** features for advanced users.

Since you're learning C#, you have to trust me when I say that it really will not matter which version of .NET Core you download and install.  The videos on this site will always work with any version 3.1 or greater.  When there is a significant difference, I'll make sure to let you know and label it clearly.

I'll click the link to download .NET Core SDK and launch it once it is ready.

We'll accept all the default options.

-----------------------------------------

Once it's finished, open the Windows COmmand Prompt and type `dotnet --version` and you should see version 3.1 or greater.  This launches the dotnet CLI, or Command Line Interface, which is what we'll be using for many of the tutorials on this site.  The dotnet cli gives you access to many features of dotnet, including the C# compiler and templates for creating new projects and files.  I'll explain some of this in the level 1 course, "dotnet CLI Level 1 - Getting Started".

And it looks like dotnet is working and ready to go!