# What is .NET?

.NET is “an open source developer platform, created by Microsoft, for building many different types of applications. You can write .NET apps in C#, F#, Visual C++, or Visual Basic.”

When you download .NET, you’re really downloading a bunch of programs that:

- Translate your C# code into instructions that a computer can understand
- Provide utilities for building software, like tools for printing text to the screen and finding the current time
- Define a set of data types that make it easier for you to store information in your programs, like text, numbers, and dates

# To install .NET, you can either use the .NET  standalone installer or install it alongside Visual Studio Code.

To install .NET using the standalone installer:

- Go to the .NET download page and download the installer for your operating system.
- Run the installer and follow the on-screen instructions.
- Once the installation is complete, you will have the .NET  SDK and runtime installed on your computer.
  
To install .NET alongside Visual Studio:

- Download and install Visual Studio.
- Download and install the .NET SDK.
- Once you have .NET installed, you can start developing .NET applications. To do this, you can use Visual Studio.

Here are the steps to install .NET on different operating systems:

# Windows:

- Download the .NET standalone installer from the .NET download page.
- Run the installer and follow the on-screen instructions.
- Once the installation is complete, you will have the .NET SDK and runtime installed on your computer.
  
# MacOS:

- Download the .NET standalone installer from the .NET download page.
- Double-click the installer file to start the installation process.
- Follow the on-screen instructions to complete the installation.
  
# Linux:

Open a terminal window.
- Install the .NET SDK using your package manager.
- For example, on Ubuntu, you would run the following command:
- sudo apt install dotnet-sdk-7.0
  
To verify that .NET is installed correctly, run the following command:
- dotnet --info
  
You should see output similar to the following:

- .NET SDK (7.0.100)
- Product Version: 7.0.100
- Once you have .NET installed, you can start developing .NET applications.

  re are some additional tips for installing .NET with Visual Studio 2022:

- If you are installing Visual Studio 2022 on a new computer, you may need to install the .NET Framework before you can install Visual     Studio.
- If you are upgrading to Visual Studio 2022 from a previous version of Visual Studio, your existing .NET installation will be upgraded.
- You can also install multiple versions of .NET on your computer. To do this, use the .NET standalone 

- Create a project in visual studio
- Go to the project path, in terminal create a folder(publish) then enter dotnet publish --self-contained -r osx-arm64 -p:PublishSingleFile=true -o arm64(For mac)

   


  <img width="862" alt="Screenshot 2023-11-06 at 11 00 35 PM" src="https://github.com/UniversityOfAppliedSciencesFrankfurt/se-cloud-2023-2024/assets/148810715/24973998-d1c5-467b-92fc-df5b83e69aa2">


  
- Run the project in debugger mode, debug--attach to process, search app name

  
<img width="1440" alt="Screenshot 2023-11-06 at 11 06 38 PM" src="https://github.com/UniversityOfAppliedSciencesFrankfurt/se-cloud-2023-2024/assets/148810715/8ebe548c-10da-4e84-893b-4fa7bbe3f39f">

- Open debug -- windows -- modules

  <img width="1090" alt="Screenshot 2023-11-06 at 11 08 11 PM" src="https://github.com/UniversityOfAppliedSciencesFrankfurt/se-cloud-2023-2024/assets/148810715/9137559e-0f70-4e7a-aa43-a3d057bc40aa">

# Libraries in C#

Creating libraries in C# involves encapsulating reusable code into a separate assembly that can be referenced and utilized by other C# projects. Here are the general steps to create a library in C#:

1. Create a New Class Library Project:
- Open Visual Studio.
- Select "File" -> "New" -> "Project...".
- Choose "Class Library" from the available project templates.
- Provide a name for your library and choose a location.
- Click "Create" to generate the project.

2. Write Code in Your Library.
   
3. Use Your Library in Another Project:
- Create a new C# project (Console Application, Windows Forms, etc.).
- Right-click on the project in Solution Explorer.
- Choose "Add" -> "Reference...".
- Browse and select the .dll file of your library.
- Click "Add" and then "OK".

# Nuget package

NuGet is a package manager for C# and .NET projects. It helps developers manage dependencies by allowing them to easily install, update, and remove packages that contain reusable code and resources. NuGet packages are distributed through package feeds, and developers can use tools like the Package Manager Console in Visual Studio or the .NET CLI to work with them. This simplifies the process of integrating third-party libraries and components into C# projects.

# Testing Frameworks in C#:

 - NUnit: A mature and widely used framework for writing unit tests in C#. It provides a simple syntax and a rich set of features, including assertion methods, mocking frameworks, and test runners.

 - xUnit: A modern and popular testing framework for C#, known for its flexibility and extensibility. It offers a concise syntax, a variety of assertions, and integration with various build tools and IDEs.

 - MSTest: A lightweight testing framework provided by Microsoft, specifically designed for .NET applications. It's easy to learn and use, and it integrates seamlessly with Visual Studio.

