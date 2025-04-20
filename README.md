# <img src="https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/jsopx-aspnet-core-logo.svg" style="width: 28px; height: auto; padding-right:12px;!important;"> JSopX™ Asp.Net Core Project

The **JSopX™ Asp.NET Core Project** is a **FREE**, open-source demonstration project built in Visual Studio, _code named_, `JSopX.AspNetCore`. It showcases the transformation of an existing ASP.NET Core application—complete with its own assets, Web APIs, and standards—into a scalable solution for optimal enterprise application migration.

---

## **Use Latest Variant:**

> [!TIP]
> You are currently viewing the **"_Use Latest_" _Variant_** of the **JSopX™ Asp.Net Core Project**. 
> 
> For more details, see [Getting Started](#getting-started) _below_.

---

```bash
# For The Cool Kids: Clone JSopX.AspNetCore Git Repository
$ git clone https://github.com/JasonSilvestri/JSopX.AspNetCore.git
```

---

[`Home`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/README.md) » [`Introduction`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/) » [`Projects`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/) · · **`Use Latest`** · [`By-Phase`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/README.md) · [`From Scratch`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/RECREATEME.md) · · [`« Previous`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.RCLxComponents/) [`Next »`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AngularCore/)

---

![Jason Silvestri Open Project EXperiences (JSopX™) 0. JSopX™ Enterprise Solution Asp.NET Core Splash](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-0.png)

## Table of Contents  

 - [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Corequisites](#corequisites)
  - [Business Concerns Addressed](#business-concerns-addressed)
  - [Getting Started](#getting-started)
      - [Step 1: Clone the Repository](#step-1-clone-the-repository)
      - [Step 2: Open the Solution](#step-2-open-the-solution)
      - [Step 3: Configure the Project](#step-3-configure-the-project)
      - [Step 4: Build and Run](#step-4-be-sure-to-build-and-run)
      - [Step 5: Project File Structure](#step-5-project-file-structure)
      - [Step 6: Project References & Dependencies](#step-6-jsopx-project-references--dependencies)
      - [Step 7: Usage](#step-7-usage)
      - [Step 8: Extended Usage](#step-8-extended-usage)
  - [Next Steps](#next-steps)

---

## Overview

The **JSopX™ Asp.NET Core Project** is a **FREE**, open-source demonstration project built in Visual Studio, _code named_, `JSopX.AspNetCore`. It showcases the transformation of an existing ASP.NET Core application—complete with its own assets, Web APIs, and standards—into a scalable solution for optimal enterprise application migration.

By aligning varied frameworks—ranging from [ASP.NET Core](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/README.md) to [Angular](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AngularCore/README.md), [Vue](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.VueCore/README.md), [React](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.ReactCore/README.md), [Blazor](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.BlazorServerCore/README.md), [MAUI](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.MauiHybridNetCore/README.md) and more, all using the same [Web API](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.WebAPI/README.md), [assets](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.RCLxProper/README.md), [documentation](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.BridgeTooFar/README.md), and [standards](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxDevelopmentStandards.md)—these projects create a consistent development landscape where code can be shared, extended, and integrated seamlessly, bridging-of-the-critical-gap, between front-end dynamism and back-end security. 


[`Back to Top`](#table-of-contents) 

---

## Current Phase

> [!CAUTION]
>
>**Phases 1**: This document is currently aligned with [Phase 1: Minimum Viable Product (MVP)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Phases/Phase-1.md) Business Requirements. 
> 

---

## **Prerequisites**

Be sure each technology is installed, with proper versioning, if your goal is to continue exploring and/or installing just the `JSopX.AspNetCore` Project.

- [Visual Studio (v 17.13.6)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)
- [.NET Framework (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#net-framework)
- [ASP.NET Core (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#aspnet-core)

---

## Corequisites

There are a few resourcees here that strongly align with this content. They should be strictly followed as you go. 

- [Development Standards](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxDevelopmentStandards.md)
- [Business Requirements](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxEnterpriseBusinessRequirements.md)

---


## Business Concerns Addressed

The **JSopX™ Asp.Net Core Project** addresses **several** high-level **business concerns**, not only shown through design patterns and best practices within its own JSopX™ Project ecosystem, but ultimately as it evolves into a valuable project component of the Jason Silvestri Open Project EXperiences (JSopX™) Enterprise Application too. 

While this ASP.NET Core project often looks and feels like a standard server-side solution, it underpins the security, routing, and scalability principles that define the JSopX™ environment.

[`Back to Top`](#table-of-contents) · · [`Next »`](#1-simulating-an-existing-project)

---

## **1. Simulating an Existing Project**:

We initially create the **JSopX™ Asp.NET Core Project** to simulate an ["Existing" Server-side Apps Example](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md#6-server-side-existing-apps-examples) Weather Forecast Asp.NET Core application, with its own Web API and existing standards, to conform to the initial business requirements set forth by the fictional stakeholders.

![Jason Silvestri Open Project EXperiences (JSopX™) 1. Simulating an Existing Project](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-1.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#business-concerns-addressed) [`Next »`](#2-create-our-development-standards)

---

## **2. Create Our Development Standards**: 

JSopX™ Enterprise application development isn't just about writing code—it's about creating scalable, maintainable, and secure solutions that stand the test of time. This takes a series of disciplines that provide the framework for sustainable success, ensuring every project delivers efficiency, performance, and an exceptional developer experience.

> [!WARNING]
>
>The **biggest mistake** _businesses_ and/or their _developers_ make is not following some form of development standards.
> 

![Jason Silvestri Open Project EXperiences (JSopX™) 2. Create Our Development Standards](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-2.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#1-simulating-an-existing-project) [`Next »`](#3-multi-platform-creative-standards)

---

## **3. Multi-Platform Creative Standards**: 

A visually inconsistent application creates confusion. Every JSopX™ project must maintain standardized UI/UX elements. We quickly design and customize multi-platform, web, desktop & native mobile applications, using Bootstrap v 5.3, which we then extend as we go by creating RCLs (_Razor Class Libraries_). 

![Jason Silvestri Open Project EXperiences (JSopX™) 3. Multi-Platform Creative Standards](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-3.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#2-create-our-development-standards) [`Next »`](#4-using-object-oriented-programming)

---

## **4. Using Object-Oriented Programming**:

Enterprise applications must be **modular**, **reusable**, and **scalable** using **Object-Oriented Programming (OOP)**. 

We create Classes, RCLs, Web APIs, and other Resource Libraries, sharing resources across the JSopX™ ecosystem seamlessly. More rewarding, because we put the work in up front with developing & following standards, developers get to work on cooler things they are more passionate about too, like _Feature Highlights_.

![Jason Silvestri Open Project EXperiences (JSopX™) 4. Using Object-Oriented Programming](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-4.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#3-multi-platform-creative-standards) [`Next »`](#5-we-get-to-extend-existing-project)

---

## **5. We Get to Extend Existing Project**:

As the project evolves through each Lifecycle Phase, we extend the application by creating new user interfaces, such as dashboards, logins, registration, in addition to being able to apply the standardized assets and resources we took the time to develop, implement security and writing documentation a well oiled machine and team relies on, and more!

![Jason Silvestri Open Project EXperiences (JSopX™) 5. We Get to Extend Existing Project](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-5.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#4-using-object-oriented-programming) [`Next »`](#6-we-become-a-functioning-project-of-the-jsopx-enterprise-solution)

---

## **6. We Become A Functioning Project of the JSopX™ Enterprise Solution**:

The seamless integration into an enterprise-level application, adopting standardized Web API access, design patterns, and shared resources across the ecosystem.

![Jason Silvestri Open Project EXperiences (JSopX™) 6. We Become A Functioning Project of the JSopX™ Enterprise Solution](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/blob/master/JSopX.BridgeTooFar/doc-assets/for-docs/jsopx-aspnet-core/in-markdown/aspnet-splash-simulate-container-markdown-step-6.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#5-we-get-to-extend-existing-project) [`Next »`](#getting-started)

---

## **Getting Started**

Carefully _choose_ the variant approach below that fits your current objective:

---

### 1. **`Continue` Exploring or Installing `JSopX.AspNetCore` Project**:

- **[Continue](#step-1-clone-the-repository)** → **Continue** as **you were**, exploring and/or installing the `JSopX.AspNetCore` _Using Latest_ Variant.  

---

### 2. **Use Different Variant**:

- [Browse By-Phase](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/README.md): **Browse** **previous versions** of the application by **phases** using the `JSopX.AspNetCore` _By-Phase_ Variant.   
- [Start From Scratch](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/RECREATEME.md): **Create project** from scratch, step-by-step, using the `JSopX.AspNetCore` _From Scratch_ Variant.
- [Get All Projects](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.OpenProjectX/README.md): **Get all projects** instead, using the `JSopX.OpenProjectX` Enterprise Application.

---

## **Step 1: Clone the Repository**

_Clone_ the `JSopX.AspNetCore` GitHub Repository if you plan to explore it independently from the rest of the projects.

Choose the approach below that fits your environment:  

- **[Bash](#step-11-using-bash)** → Ideal for **Linux, macOS, and Windows (WSL/Git Bash)** users.  
- **[PowerShell](#step-12-using-powershell)** → Best for **Windows** users.  
- **[Node.js](#step-13-using-nodejs-or-npm-degit)** → A lightweight option for developers using **JavaScript-based workflows**.  

---

### **Step 1.1: Using `Bash`:**
 
```bash

 # Using Bash: Clone JSopX.AspNetCore Git Repository

 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\JSopX.AspNetCore

 # 2. Clone JSopX.AspNetCore Git Repository       
 git clone https://github.com/JasonSilvestri/JSopX.AspNetCore.git
    
```

[`Back to Top`](#table-of-contents)

---

### **Step: 1.2: Using `Powershell`:**

```powershell

 # Using PowerShell: Clone JSopX.AspNetCore Git Repository

 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\JSopX.AspNetCore

 # 2. Clone JSopX.AspNetCore Git Repository       
 git clone https://github.com/JasonSilvestri/JSopX.AspNetCore.git
    
```

[`Back to Top`](#table-of-contents)

---

### **Step: 1.3: Using `Node.js` or `npm` (degit):**
 
```shell

 # Using Node.js / npm : Clone JSopX.AspNetCore Git Repository
 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\JSopX.AspNetCore
    
 # 2. Using npx degit to clone without .git history
 npx degit https://github.com/JasonSilvestri/JSopX.AspNetCore

```

[`Back to Top`](#table-of-contents)

---

## **Step 2: Open the Solution**

Working with the `JSopX.AspNetCore` Project in Visual Studio is simple enough.

1. Launch **[Visual Studio (v 17.13.6)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)**.
2. Open the solution file: `JSopX.AspNetCore.sln`.

[`Back to Top`](#table-of-contents)

---

## **Step 3: Configure the Project**

> [!TIP]
>
> Latest versions of [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio) performs this step regularly, dropping and restoring project dependencies, nuget packages and other resources between builds automatically (*by design*). Still, it is good practice to at least be aware of the commands outlined in this step.
> 

---

### **Step: 3.1: Ensure Dependencies Are Restored:**

Ensure `JSopX.AspNetCore` Project dependencies are restored:

   ```bash
   npm install
   ```


[`Back to Top`](#table-of-contents)

---

### **Step: 3.2: Verify Nuget Packages:**

Verify that all NuGet packages are up to date:

   ```bash
   dotnet restore
   ```
   
[`Back to Top`](#table-of-contents)

---

## **Step 4: Be Sure to Build and Run**

Building and Running the `JSopX.AspNetCore` Project in Visual Studio is also another simple task.

### **Step: 4.1: Build and Run**:

1. Build the solution in [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/Technologies/#visual-studio).
2. Run the project:
   - Use the **IIS Express** profile for local development.

---

### **Step: 4.2: And Now Your Done**:

Assuming the `JSopX.AspNetCore` Project is running as expected, **you are now done** with the **installation** and **execution** of the project!

1. **Skip Remaining Steps**: 
   - Technically, you could skip to the [Next Steps](#next-steps) section if you are on a project-by-project installation mission.
2. **Conclude Remaining Steps**:
   - **Me personally?** I would continue on to the remaining steps _below_, starting at **[Step 5: Project Structure](#step-5-project-file-structure)**. There is just very useful information related to the project that I would find helpful.

[`Back to Top`](#table-of-contents)

---


## **Step 5: Project File Structure**

The `JSopX.AspNetCore` Project in particular, contains several files and directories, all with their own functionality & purpose for existing. 

For brevity, samples will not have the complete file structure you get when installing, but there are some core files and directories that have special consideration you should get to know. 

---

### **Step: 5.1: Structured Project & Solution Considerations**:

All `JSopX™ projects` follow a consistent directory structure, based on its [JSopX™ Project Family](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md) (_relatively speaking_). 

1. The `JSopX.AspNetCore` Project naming conventions include capital casing for `.Server` directories.
2. I create a [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/Technologies/#visual-studio) Solution Folder to house the primary `.sln` solution file.
3. I create a Server-Side Project Folder for `.csproj`, and related files.

A common, plain-text file folder structure of the `JSopX.AspNetCore` Solution and Projects should look something like what follows:

```plaintext
# JSopX™ Asp.Net Core Solution and Projects

JSopX.AspNetCore/                 # Root JSopX.AspNetCore Visual Studio Solution folder.
├── JSopX.AspNetCore.sln          # Visual Studio '.sln' solution file for Asp.Net Core.
├── PathConfig.targets            # Centralized MSBuild target configuration for project references.
├── JSopX.AspNetCore/             # Asp.NET Core server-side application folder.
│   ├── JSopX.AspNetCore.csproj   # Asp.NET Core Visual Studio Server Project '.csproj' configuration file.

```

There are a few reasons why I do this, but the primary reason is ensuring references are managed effectively and circular dependencies are avoided.

[`Back to Top`](#table-of-contents)

---

### **Step: 5.2: Structured File Tree**:

A common, plain-text file structure of the `JSopX.AspNetCore` Project files and directories that matter.

```plaintext
# JSopX™ Asp.Net Core Project

JSopX.AspNetCore/                            # Root JSopX.AspNetCore Visual Studio Solution folder.
├── .gitattributes                           # Git attributes file for repository metadata and configurations.
├── .gitignore                               # Specifies files and directories to ignore in version control.
├── JSopX.AspNetCore.sln                     # Visual Studio '.sln' solution file for Asp.Net Core.
├── LICENSE.txt                              # Licensing information for the project.
├── PathConfig.targets                       # Centralized MSBuild target configuration for project references.
├── README.md                                # High-level project documentation.
├── JSopX.AspNetCore/                        # ASP.NET Core Server-side application folder.
│   ├── JSopX.AspNetCore.csproj              # ASP.NET Core Visual Studio Project '.csproj' configuration file.
│   ├── Program.cs                           # Main entry point for the ASP.NET Core server.
│   ├── Controllers/                         # API controllers exposing server endpoints.
│   ├── appsettings.json                     # Application settings file for configuration.
│   └── WeatherForecast.cs                   # Example Weather Forecast model class (default template).

```

[`Back to Top`](#table-of-contents)

---

### **Step: 5.3: Structured Table**:

A table structure of the same with no tree legs `JSopX.AspNetCore` Project, files and resources.


| **File/Directory**                        | **Description**                                                                                   |
|:------------------------------------------|:--------------------------------------------------------------------------------------------------|
| &nbsp;📁&nbsp;**JSopX.AspNetCore/**&nbsp;                | Parent `JSopX.AspNetCore` Visual Studio Solution folder, containing both client and server code.|
| &nbsp;├&nbsp;📝&nbsp;`.gitattributes`&nbsp;                   | Git attributes file for repository metadata and configurations. |
| &nbsp;├&nbsp;📝&nbsp;`.gitignore `&nbsp;                      | Specifies files and directories to ignore in version control. |
| &nbsp;├&nbsp;📝&nbsp;`JSopX.AspNetCore.sln`&nbsp;            | Visual Studio `.sln` solution file linking the client and server projects. |
| &nbsp;├&nbsp;📝&nbsp;`LICENSE.txt`&nbsp;                      | Licensing information for the project (generally `MIT` open-source license). |
| &nbsp;├&nbsp;📝&nbsp;`PathConfig.targets`&nbsp;               | Centralized MSBuild target configuration for project references, used in conjunction with Git Sub Trees, to retain all files and references, while dynamically resetting reference paths if necessary. |
| &nbsp;├&nbsp;📝&nbsp;`README.md`&nbsp;                      | The current, most recent, primary project README `.md` file. |
| &nbsp;├&nbsp;📁&nbsp;**JSopX.AspNetCore**&nbsp;         | Asp.NET Core server-side folder for back-end logic and API endpoints. |
| &nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`JSopX.AspNetCore.csproj`&nbsp;     | Asp.NET Core server-side Visual Studio project `.csproj` configuration file. |
| &nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`Program.cs`&nbsp;                       | Main entry point for the ASP.NET Core application, initializing services. |
| &nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📁&nbsp;**`Controllers/`**&nbsp;                     | Contains API controllers that handle HTTP requests and responses. |
| &nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`appsettings.json`&nbsp;                 | Configuration file for application settings like connection strings. |
| &nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`WeatherForecast.cs`&nbsp;               | Example Weather Forecast model class provided by ASP.NET Core templates for demonstration. |

[`Back to Top`](#table-of-contents)

---

## **Step 6: JSopX™ Project References & Dependencies**

> [!TIP]
>
> The `JSopX.AspNetCore` Project should already have the JSopX™ Project References & Dependencies described below included!
> 

---

Most `JSopX™ Projects` leverage shared resources and code from other projects within the JSopX™ ecosystem. This ensures modularity, maintainability, and scalability.

The `JSopX.AspNetCore` Project has the following `JSopX` Project Dependencies:

1. **`JSopX.BridgeTooFar`**:
   - A [Shared Assets & Resources Projects](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md#2-shared-assets--resources-projects) that contains reusable static assets and project documentation.
   - **Explore GitHub**: [JSopX.BridgeTooFar](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.BridgeTooFar)

2. **`JSopX.ClassLibrary`**:
   - A [Shared Data, Service & Function Project](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md#3-shared-data-service--function-projects) that houses shared business logic and helper methods.
   - **Explore GitHub**: [JSopX.ClassLibrary](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.ClassLibrary)

3. **`JSopX.WebAPI`**:
   - A [Shared Data, Service & Function Project](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md#3-shared-data-service--function-projects) which acts as the centrialized **Web API**, used by all projects that access data endpoints in the application.
   - **Explore GitHub**: [JSopX.WebAPI](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.WebAPI)
 
4. **`JSopX.RCLxProper`**:
   - An extremely light-weight, [Shared Assets & Resources Projects](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/JSopxProjectsFamilies.md#2-shared-assets--resources-projects) version of the `JSopX.Assets` Razor Class Library, specifically designed for Production-Ready environments.
   - **Explore GitHub**: [JSopX.RCLxProper](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.RCLxProper)


[`Back to Top`](#table-of-contents)

---

## **Step 7: Usage**

Although the `JSopX.AspNetCore` project is primarily designed as a self-contained demonstration project, it is fully capable of integration with other JSopX™ projects. Here's how to add it to your project:

---

### **Step 7.1: Adding the JSopX™ Asp.Net Core to Other Projects**

1. **Add Project Reference**:
   - Open your solution in Visual Studio.
   - Right-click the project that will use `JSopX.AspNetCore` and select `Add > Project Reference`.
   - Check the box for `JSopX.AspNetCore` and click `OK`.

[`Back to Top`](#table-of-contents)

---

## **Step 8: Extended Usage**

> [!TIP]
> These particular `Extended Usage` examples **are not** required to implement. They are just example extended usages for those of whom are new to projects like the `JSopX.AspNetCore` Project.
>

---

## **Step 8:1. Extend Angular Client Project**

1. Modify the `proxy.conf.js` file to configure the API URL.
2. Use Angular services to consume APIs exposed by the server project.

   **Example service file in `Angular`**:
   ```typescript
   import { HttpClient } from '@angular/common/http';
   import { Injectable } from '@angular/core';

   @Injectable({
     providedIn: 'root',
   })
   export class ExampleService {
     private apiUrl = 'https://localhost:5001/api/example';

     constructor(private http: HttpClient) {}

     getExampleData() {
       return this.http.get(`${this.apiUrl}`);
     }
   }
   ```
 
[`Back to Top`](#table-of-contents)

---

### **Step 8:2. ASP.NET Core Server Project**

1. Add dependency injection for shared services in `Program.cs`:

   ```csharp
   builder.Services.AddScoped<ExampleService>();
   ```

2. Create or modify controllers to expose endpoints:

   ```csharp
   [ApiController]
   [Route("api/[controller]")]
   public class ExampleController : ControllerBase {
       private readonly ExampleService _service;

       public ExampleController(ExampleService service) {
           _service = service;
       }

       [HttpGet]
       public IActionResult GetExample() {
           var data = _service.GetExampleData();
           return Ok(data);
       }
   }
   ```

[`Back to Top`](#table-of-contents)

---

## **Next Steps**

Carefully choose the approach below that fits your current objective:

---

- **[Continue](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AngularCore/README.md)** → _Continue_ as **you were**, exploring and/or installing other projects like you did with **this project**. You'll move onto the next project, using the `JSopX.AngularCore` _Using Latest_ Variant.  

---

- [Browse By-Phase](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/README.md): **Browse** **previous versions** of the application by **phases** using the `JSopX.AspNetCore` _By-Phase_ Variant.   
- [Start From Scratch](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/RECREATEME.md): **Create project** from scratch, step-by-step, using the `JSopX.AspNetCore` _From Scratch_ Variant.
- [Get All Projects](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.OpenProjectX/README.md): **Get all projects** instead, using the `JSopX.OpenProjectX` Enterprise Application.

---

[`Home`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/README.md) » [`Introduction`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/) » [`Projects`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/) · · **`Use Latest`** · [`By-Phase`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/README.md) · [`From Scratch`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AspNetCore/p1/v1/RECREATEME.md) · · [`Back to Top`](#table-of-contents) · [`« Previous`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.RCLxComponents/) [`Next »`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.AngularCore/)

---

##### [JSopX.com](https://www.jsopx.com/) | [Jason's Official Website](https://www.jsilvestri.com/) | [X](https://www.x.com/JasonSilvestri) | [LinkedIn](http://www.linkedin.com/in/JasonSilvestri) | [GitHub](https://github.com/JasonSilvestri) | [Gmail](mailto:therealjasonsilvestri@gmail.com) | [Phone : 508-851-9445](phoneto:508-851-9445)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri
