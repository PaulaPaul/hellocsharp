Back to Basics: Hello C#
========================

If you want to have some fun with a Microsoft .NET evangelist, ask them to write a simple console app that just prints 'Hello C#!' to the console.

What's fun about that? 
Ask them to do it using Notepad, or their favorite text editor (not using Visual Studio.)

Here's one way to do it.  It's interesting to note how much additional code is created when you use Visual Studio.

To compile a .cs file from the command prompt:
----------------------------------------------
* Search for 'csc.exe' on your system (for example it may be found in C:\Program Files (x86)\MSBuild\14.0\Bin).  Add the location to your path.

* Create an executable file from your .cs source (for example):
	csc hellocsharp.cs

Once you have an executable file, you know what to do...
	Note: If you are using Git bash, use bash syntax to run from the command prompt: ./hellocsharp.exe