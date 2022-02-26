![Nuget Version](https://img.shields.io/nuget/v/DougMurphy.Templates.NuGetPackage?label=nuget.org)
![Nuget Downloads](https://img.shields.io/nuget/dt/DougMurphy.Templates.NuGetPackage)

# Introduction

Creating a NuGet package is easy. Creating a NuGet package with all of the proper bells and whistles can be surprisingly tricky!
There are many things that you must remember to do, and not all of them are obvious or easy to discover.
This template aims to solve that problem by providing an extremely simple way to create a NuGet package that includes all of the best practice recommendations by Microsoft out of the box for you!

# Installation and Usage

Installing dotnet templates is easy! Just run the following command in your terminal: `dotnet new -i DougMurphy.Templates.NuGetPackage`

Before using this template, you may want to reinstall the template to ensure that you have all of the latest changes.
To reinstall the template, run the following commands in your terminal:
1. `dotnet new -u DougMurphy.Templates.NuGetPackage`
2. `dotnet new -i DougMurphy.Templates.NuGetPackage`

When you are ready to create your package, run the following command in your terminal: `dotnet new dmurphy.nuget -n <your-package-name>`.
This will create a folder in the current directory with the name you specified, as well as all of the files and folders that are included in the template.

If you need to see any details about the template, you can run the following command in your terminal: `dotnet new dmurphy.nuget -h`

# Contributing

If you have any questions or have come across a bug, please open an issue [here](https://github.com/Doug-Murphy/DougMurphy.Templates.NuGetPackage/issues/new).
If you want to contribute a change to the template, please open a pull request [here](https://github.com/Doug-Murphy/DougMurphy.Templates.NuGetPackage/compare).