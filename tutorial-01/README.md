# <a href="https://github.com/Aoa77/visual-studio-tutorials/blob/main/tutorial-01/README.md">Build an app with React, TypeScript, .NET Core Web API, and Azure Blob Storage</a>
In this tutorial, we will use Visual Studio 2022 to scaffold a full-stack application with a frontend React project and a backend ASP.NET Core project. We'll learn how to add new React UI components with TypeScript and NPM, and we'll add data persistance to the backend API using Azure Blob Storage. 

<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/Visual-Studio.png" title="Visual Studio 2022" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/React.png" title="React" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/TypeScript.png" title="TypeScript" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/Vite.png" title="Vite" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/.NET-core.png" title="ASP.NET Core" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/Swagger.png" title="Swagger" />&nbsp;
<img width="16" src="https://raw.githubusercontent.com/Aoa77/visual-studio-tutorials/main/devicon/png-512/Azure.png" title="Azure" />


&nbsp;

## `STEP 01`
Assuming you have Visual Studio 2022 installed, open the Visual Studio Installer application, click the "Modify" button, and verify or install the following three components under the "Web & Cloud" workload category. 
- ASP.NET and web development
- Azure development
- Node.js development

https://github.com/Aoa77/visual-studio-tutorials/assets/4643190/ec21d4e1-adac-439c-a852-c7b486b32773


&nbsp;

## `STEP 02`
Launch Visual Studio 2022, click "Create New Project", then choose the project template "React and ASP.NET Core" with Typescript. 

https://github.com/Aoa77/visual-studio-tutorials/assets/4643190/e24fad7c-1d21-46d6-9b9b-8bcb8158357f


&nbsp;


## `STEP 03`
Once Visual Studio finishes creating the solution, verify that you have a new <b>`Tutorial_01.sln`</b> file with two projects listed in the Solution Explorer: 
- <b>`tutorial_01.client`</b> - this is the frontend web application built with React, Typescript, and Vite.
- <b>`Tutorial_01.server`</b> - this is the backend REST API built with .NET Core and Swagger.

https://github.com/Aoa77/visual-studio-tutorials/assets/4643190/7b960572-de78-4670-b3f0-575fd61cd7f7



