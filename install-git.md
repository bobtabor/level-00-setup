Git is source code management software from the creator of Linux.  In a relatively short time, it became the most popular tool of its kind, and has become a critical part of learning how to code.  At a high level, source code management software allows you to:

- share your code with others, and accept their contributions to your code by merging their changes into your code

- take snapshots of the current state of the project at a moment in time, then go back to a snapshot if necessary

Unfortunately, learning git requires a significant amount of time, and we'll devote many courses to Git. You might wonder "Just how hard can it be?" You'll have to take my word for it, there's a lot of complexity there and feeling confident in Git takes time.  We'll take baby steps, and the first is just to install it on your local computer so you can download the source code I'll write, and the source code you'll use as a starting point for various exercises and challenges.

Git's installation wizard presents you with a lot of options. Many of the options reflect the fact that Git is fundamentally a Linux-based application running on Windows, so it will ask how to handle special cases where Windows and Linux are different.

For our purposes, selecting the default options will work just fine.

To download, go to your favorite search engine and search for "git download". That should take you to a web page on the domain git-scm.com ... make sure you don't get fooled into downloading from a different source.

Download the most recent version, and install.

Again, the default options will work fine. If you ever need to change the default settings, we can do so from simple ASCII text files.

----------------------------------

At the end of the process, you may see an option to launch Git Bash.  Git was created originally for Linux, and porting it to Windows required a separate effort.  In fact, when you install Git, you're really installing "Git for Windows".  You can learn more at gitforwindows.org.

"Git for Windows" installs:

- Git, compiled for Windows users
- Git Bash, a command line interface that emulates the popular Linux command language interpreter Bash.
- Git GUI, which is a graphical user interface that performs Git commands
- Shell Integration, which allows you to open Git Bash or Gui GUI from Windows Explorer.

Frankly, you won't need any of this.

All you need is the command prompt, also known as cmd.  It's also known by many other nick names like "the command line", "the DOS prompt", "Windows command line" and others.  If it has to do with the command line on Windows, it likely means we're talking about "cmd".

To launch "cmd", just use the Windows key on your keyboard to search installed apps, and type "cmd".  I recommend pinning it to the Windows Task Bar, and moving it into the first position so you can use the Windows key and the number 1 to launch it.

Just to confirm that you can acces git commands from the command prompt:

git --version

And it looks like Git is working and ready to go!

