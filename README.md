# TypescriptPIAIC
All Typescript Practice Assignments of Web3.0 Classes (October 2023)
        // Download Instructions (package-lock.json & package.json)
        https://www.typescriptlang.org/download
via npm
TypeScript is available as a package on the npm registry available as "typescript".

You will need a copy of Node.js as an environment to run the package. Then you use a dependency manager like npm, yarn or pnpm to download TypeScript into your project.

npm install typescript --save-dev

npm yarn pnpm
All of these dependency managers support lockfiles, ensuring that everyone on your team is using the same version of the language. You can then run the TypeScript compiler using one of the following commands:

npx tsc

npm yarn pnpm
with Visual Studio
For most project types, you can get TypeScript as a package in Nuget for your MSBuild projects, for example an ASP.NET Core app.

When using Nuget, you can install TypeScript through Visual Studio using:

The Manage NuGet Packages window (which you can get to by right-clicking on a project node)
The Nuget Package Manager Console (found in Tools > NuGet Package Manager > Package Manager Console) and then running:
Install-Package Microsoft.TypeScript.MSBuild
For project types which don't support Nuget, you can use the TypeScript Visual Studio extension. You can install the extension using Extensions > Manage Extensions in Visual Studio.
