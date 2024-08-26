# Execute-C-Sharp-code-without-an-IDE

**Installing Microsoft.Net Framework:**
  Download the .Net framework from the given link:
  https://dotnet.microsoft.com/en-us/download/dotnet-framework

  You can skip this if you already have a .Net framework installed on you machine.
  
**Setting up the Environment for C# Compiler:**
  Go to Control Panel>System and Security>System.
  Under Advanced System Setting option, select  Environment Variables.
  Under System Variables, edit the Path variable and add the path where .NET Framework is installed (Eg: C:\Windows\Microsoft.NET\Framework\v4.0.30319).
  Click OK and save the settings.

  To verify the process was right, open command prompt and type "csc" and you will see the compiler version printed.

**Steps to Execute C# Program on cmd:**
  Open any text editor and write the code that you need to execute and save it as .cs extension OR download the C# code from the repository.
  To compile the code, open CMD and navigate to the C# code file location and type "csc C#FileName.cs"

  If there are no errors in the code, this will create a .exe file in the same location.
  
  To execute the generated exe file in CMD, navigate to the generated .exe file location and type the file name and ENTER, it will execute and the output can be obtained.
  Also, the generated .exe file can be executed by opening it directly.
