# Section 2 - C# Crash Course - Basics

## Lecture 1 - Basic Theory Pt 1

### Learning Objectives

- **Create a Console Application**
  - Ideal for understanding the fundamentals
  - Provides immediate feedback, allowing for easier observation of code results

- **Basic Concepts**
  - **Console.WriteLine()**
    - Outputs text to the console
    - Essential for visualizing code outcomes
  - **Variables**
    - Explores the variety of variable types in C#
    - Demonstrates declaration and usage
  - **Operators**
    - Covers arithmetic operators (addition, subtraction, multiplication, division, modulus)
    - Explains their role in variable manipulation
  - **Conditional Statements**
    - Emphasizes if statements
    - Details the conditions under which these statements execute
  - **Loops**
    - Introduces for, foreach, while, and do-while loops
    - Discusses their applications
  - **Methods / Arguments / Return**
    - Guides on defining methods
    - Describes passing arguments and returning values
  - **Scope**
    - Clarifies variable scope and its effect on variable visibility and life cycle

- **Intermediate Concepts**
  - **Models**
    - Describes how to map database tables or data structures in C#, facilitating structured data representation
  - **NameSpaces**
    - Explains the role of NameSpaces in code organization
    - Highlights their utility in grouping related classes and methods
  - **Database Connection**
    - Teaches database connectivity, with a focus on MS SQL Server
    - Outlines steps for data storage and retrieval
  - **Config**
    - Discusses the use of configuration files for storing settings like database connection strings
    - Illustrates the advantages of configuration files, such as facilitating changes without needing to recompile code
  - **Reading/Writing to Files**
    - Presents file I/O operations
    - Covers reading from and writing to text files for purposes like logging and data storage
  - **Parsing JSON**
    - Explains parsing JSON data to and from models, enabling data exchange within an application or with external services
  - **Simple Model Mapping**
    - Addresses data conversion between different formats or structures
    - Stresses its importance in data integration and migration

## Lecture 2 - Console App Theory

### Creating a Console Application

- Create a Console Application
- **Use of `dotnet new` Command**
  - `dotnet new <Template Type>` &rarr; Essential for creating a new project with a specified template type
- **Template Types**
  - `dotnet new console` to create a basic console application
  - `dotnet new webapi` for web API projects
  - `dotnet new gitignore` to create a `.gitignore` file
- **Flags for Customization**
  - `-n <App Name>` or `--name <App Name>` &rarr; Sets the application and NameSpace name
  - `-o <Output Directory>` or `--output <Output Directory>` &rarr; Specifies the project's output directory. By default, the output directory is the current working directory
  - `-lang "<Language>"` or `--language "<Language>"` &rarr; Indicates the programming language (i.e., C#, F#, Visual Basic, etc.)

### Importance of Template Types and Flags

- **Template Types**
  - Allow for the creation of specific project types, streamlining the development process
- **.gitignore**
  - Essential for version control, specifying files and folders to ignore
- **Flags**
  - Provide options to customize the project's name, output directory, and programming language, enhancing project setup flexibility


### Conclusion

- The `dotnet new` command, along with its templates and flags, offers a powerful way to initiate various .NET projects, including console applications and web APIs.
- Understanding the tools and options at your disposal is crucial for efficient .NET development, as demonstrated in the upcoming practical demonstration where we will build our first application

## Lecture 3 - Creating a Console App

### Key Steps and Commands

- **Opening PowerShell**
  - Open a PowerShell window
  - Note that PowerShell defaults to the user's root directory
- **Creating a New Directory**
  - Command: `mkdir dotnet-course-code`
  - Creates a new directory (for storing course-related code)
- **Navigating to the New Directory**
  - Command: `cd dotnet-course-code`
  - Changes the current directory to the newly created folder
- **Creating the Console Application**
  - Command: `dotnet new console -n HelloWorld`
  - Successfully creates a new console application named "HelloWorld"
- **Exploring the Application Structure**
  - Command: `ls`
  - Lists the contents of the current directory, revealing the "HelloWorld" folder
  - Navigating into the "HelloWorld" directory (`cd HelloWorld`) and listing contents (`ls`) shows important files like `HelloWorld.csproj` and `Program.cs`
- **Running the Application**
  - Command: `dotnet run`
  - Executes the application, displaying the default "Hello, World!" output
  - Mention of `dotnet watch run` for automatically re-running the application upon code changes, though not demonstrated here

### Key Takeaways

- The `mkdir`, `cd`, and `ls` commands are used for directory management
- The `dotnet new` command, combined with specific flags and template types, initializes new .NET projects
- The `dotnet run` command compiles and executes the .NET application, demonstrating the immediate result of the coding effort

### Conclusion

- Lecture provides a hands-on introduction to setting up a simple "Hello, World!" console application in C#
- Emphasizes the practical aspects of using the .NET CLI for project creation and execution, setting the stage for further exploration of basic programming concepts in upcoming lectures

