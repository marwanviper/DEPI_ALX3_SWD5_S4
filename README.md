# DEPI C# and .NET Development Labs

> **Learning phase:** C# programming and .NET application-development foundations  
> **Track:** DEPI — ALX3 / SWD5 / S4  
> **Status:** Coursework archive based on the exercises present in this repository.

This repository contains a sequence of C# and .NET demonstrations and labs. It is organized by learning day and topic, making it useful as a record of progression from language fundamentals toward object-oriented programming, data access and desktop applications.

This repository is a fork of the original course repository. The upstream project and its contributors should continue to receive attribution; this README describes the learning material contained in this copy and does not claim sole authorship of the original course content.

## Repository map

```text
.
├── CsharpCourseDemos.sln
├── DotNetBefore8Demo/
├── Day2Lab/
├── Day3Lab/
├── Day4Lab/
├── Day5Lab/
├── Day6Lab/
├── Day7Lab/
├── Day8Lab/
├── Day9LabADODbConnection/
├── CleanFormDemo/
├── FirstWinFormApp/
├── IO_Demos/
└── SmartLibrary/
```

## Learning progression

| Phase | Material in the repository | Main concepts to review |
|---|---|---|
| 01 | `Day2Lab`, `Day3Lab` | C# syntax, language fundamentals and basic program structure |
| 02 | `Day4Lab`, `Day5Lab` | Classes, objects, properties and object-oriented modeling |
| 03 | `Day6Lab`, `Day7Lab`, `Day8Lab` | Inheritance, abstraction, interfaces, polymorphism and related OOP design concepts |
| 04 | `Day9LabADODbConnection` | ADO.NET database connectivity and SQL scripts |
| 05 | `FirstWinFormApp`, `CleanFormDemo`, `IO_Demos` | Windows Forms, event-driven UI and file/input-output workflows |
| 06 | `SmartLibrary` | A small library-domain project for practicing application and class design |
| Reference | `DotNetBefore8Demo` | .NET version and language-feature demonstration |

The phase labels above are a suggested learning map based on folder and file names. Consult each lab's source code to confirm the exact exercise requirements.

## Getting started

1. Install a compatible .NET SDK and Visual Studio workload for the project types you intend to run.
2. Open `CsharpCourseDemos.sln` in Visual Studio.
3. Select one lab project and set it as the startup project.
4. Restore dependencies and build that project.
5. For the ADO.NET lab, inspect the SQL scripts and update local connection settings before running.
6. For Windows Forms projects, use Windows and the appropriate desktop development workload.

The projects may target different .NET versions. Check each `.csproj` before choosing the SDK and runtime.

## How to study each lab

For every day or project, use the following cycle:

1. Read the source code before running it.
2. Write down the concept the exercise is intended to teach.
3. Run the original example and observe its behavior.
4. Reimplement the core idea without copying the original solution.
5. Change one requirement and test your implementation.
6. Record what worked, what failed and what you learned.

## Progress record

Use this table to track your own verified progress. Do not mark a phase complete simply because its folder exists.

| Phase | Status | Evidence to add |
|---|---|---|
| C# fundamentals | Needs review | Small exercises and expected output |
| Object-oriented programming | Needs review | Examples and explanations of class relationships |
| Advanced OOP concepts | Needs review | Interface, abstraction and inheritance examples |
| ADO.NET | Needs review | Database setup, SQL scripts and successful run evidence |
| Windows Forms and I/O | Needs review | Screenshots and usage notes |
| SmartLibrary | Needs review | Requirements, class diagram and example workflow |

## Repository maintenance

- Keep source code and course materials; exclude Visual Studio caches and generated build output.
- Keep secrets and local database credentials out of Git.
- Add a short README inside each lab as its requirements become clear.
- Record the .NET target framework and any external dependencies.
- Preserve upstream attribution when adapting course examples.

## Learning outcomes

The intended progression is from writing C# programs to understanding object-oriented design, working with relational data through ADO.NET and building basic desktop applications with .NET.

---
*Maintained as a record of my DEPI C# and .NET learning progression. Original course material remains attributed to its upstream authors.*
