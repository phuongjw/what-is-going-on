# May 26, 2025.

## What is a Unix shell? What are Bash and Zsh?

### What is a Unix shell?

Unix shell is a command-line interpreter or shell that provides a command line user interface (CLI) for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.

The two of the most famous shell environments are Zsh and Bash. 

### What is Bash?

Bash is a Unix-based shell and command processor that provides a CLI where you can interact with all components of your operating system by executing commands or running scripts. It offers a rich set of built-in cmmands and utilities for tasks such as file manipulation, text processing, and system administration.

### What is Zsh?

Zsh (short for Z shell) is an extended and improved version of Bash that can be used as an interactive login shell and as a command-line interpreter for shell scripting and command programming. 



## What does adding to $PATH mean?

**"Adding to $PATH"** means telling your computer where to find programs when you type a command in the terminal or command prompt.

When you type something like `java --version`, your system checks the folders listed in `$PATH` to find an executable file with that name. 

If the program is not in a folder listed in `$PATH`, you'll get an error like:

```command not found```

## What "Adding to $PATH does"

It adds the folder where your program is installed to that list -- so the system knows where to look.

Say if you installed a tool like Maven in:

```/User/phuongwj/Applications```

Then you might add this to your `$PATH` in your shell config file:

```export ....```

Now you can type:

```mvn --version```

... and it'll work from **any folder**.

Therefore, without adding to `$PATH`, you'd have to run the program by typing the full path every time.



## I've never used a Mac or a Linux before, so what is homebrew?

Homebrew is simply a free and open-source software package management system that simplifies the installation of software on Apple's operating system, macOS, as well as Linux. 

### Well, what is a package management system you wonder?

Say if you want to build something, lik a web browser maybe, and you don't want to reinvent the wheel. Therefore, you would install libraries on a computer, so that you can write codes to combine them together.

However, you need to download and install these libraries on your computer, but these libraries may need another set of libraries to be installed first. Each library will have a list of needed libraries, so you have to download and install them one by one.

That's why we need a package management system -- to automate the process of installing, upgrading, configuring, and removing computer programs for a computer in a consistent manner.

So homebrew is a tool that can automatically download all necessary projects, and automatically keep them up-to-date, in a single command. 



## What is sdkman?

First, let's understand what SDK is.

### About SDK:

SDK stands for Software Development Kit, it's a collection of tools, libraries, documentation, and APIs provided by a software or hardware vendor to help developers build applications for a specific platform.

Examples:

- Android SDK -- for building Android apps.
- iOS SDK -- for building apps for Apple devices.
- DirectX SDK -- for multimedia and gaming applications on Windows.

It's basically used by devs to quickly set up development environments or access tools to build software applications faster and in a more standardized way.

### About SDKMAN:

SDKMAN is a command-line tool that simplifies managing different version os SDKs, particularly for JVM-based (Java Virtual Machine) languages like Java, Groovy, and Kotlin.



## What is Scala?

Scala is like a smarter version of Java. It runs on the JVM, so it can use all the Java libraries, but it also lets you write code that's more concise, expressive, and powerful. You can check out the docs about Scala here: 

https://docs.scala-lang.org/



## What is AWL CLI?

AWS Command Line Interface is a powerful, open-source tool that allows you to manage and interact with AWS services from your command line or terminal



## What is LocalStack?



## What is git fetch (I've never used it)?



## What is sbt shell?



## What does it mean whenever you run "clean, reload, test" on sbt shell.



## What is Jenkins?