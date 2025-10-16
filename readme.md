# Skynet

Skynet is a living, evolving .NET series designed to help developers explore and learn about .NET technologies, tools, and best practices.

## Vision

The vision of Skynet is to provide a comprehensive and up-to-date resource for .NET developers of all skill levels. It aims to cover a wide range of topics, from the basics of C# programming to advanced concepts in ASP.NET Core, Entity Framework, and more.

### Goals

- **Modularity**: Each module focuses on a specific aspect of .NET development, allowing developers to pick and choose topics that interest them.
- **Practicality**: Real-world usage, not just theory. Each module includes code examples, tutorials, and practical applications.
- **Up-to-date**: Regularly updated to reflect the latest changes in the .NET ecosystem.
- **Community-driven**: Encourages contributions from the community to ensure a diverse range of perspectives and expertise.
- **Best practices:** Encourage clean, maintainable, and idiomatic .NET code.
- **Open-minded:** Embrace new approaches, packages, and ideas; be adaptable.

## Current .NET Versions

| .NET Version | Release Date     | Release type | End of Support   |
| ------------ | ---------------- | :----------: | ---------------- |
| `.NET 10.0`  | 11 november 2025 |    `LTS`     | 14 november 2028 |
| `.NET 9.0`   | 12 november 2024 |    `STS`     | 10 november 2026 |
| `.NET 8.0`   | 14 november 2023 |    `LTS`     | 10 november 2026 |

> For more information, visit the [.NET official website](https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core).
>
> LTS: Long-Term Support, STS: Standard-Term Support

## [Modules](./modules/readme.md)

Each module focuses on a specific aspect of .NET development, providing in-depth tutorials, code examples, and practical applications. The modules include:

- [.NET Ecosystem](./modules/dotnet-ecosystem/readme.md)
- [C# language features](./modules/language/readme.md)

## How to Use This Repository

To get started with Skynet, follow these steps:

### Prerequisites

- [.NET 10.0 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- Any IDE or text editor of your choice (e.g., Visual Studio, Visual Studio Code, JetBrains Rider)

> The SDK includes everything you need to build and run .NET applications on your machine.

You can clone this repository to your local machine using the following command:

```bash
git clone https://github.com/kappaduck/skynet.git
cd skynet
```
### Explore the Modules

Navigate to the `modules` directory to find the various modules available. Each module contains its own `readme.md` file with detailed information and instructions.

Some features/topics may require additional setup or dependencies, which will be detailed in their respective `readme.md` files. Also, some features may not be available in all .NET versions, so please check the compatibility notes in each module.

### Running the Code Examples

Some features or topic is a C# file that can be run directly using the .NET CLI. For example, to run a specific feature, navigate to its directory and use the following command:

> Any IDE doesn't support single-file execution, so you will need to run as cli.
>
> Visual Code has intellisense support for single-file but can't run it  directly.

```bash
dotnet ./top-level.cs
```
## Tools and Resources

Here are some useful tools and resources to help you

- [.NET Documentation](https://learn.microsoft.com/en-us/dotnet/)
- [C# Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [What's new in .NET](https://learn.microsoft.com/en-us/dotnet/core/whats-new/)
- [What's new in ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/whats-new/)
- [Sharplab](https://sharplab.io) - Shows intermediate steps and results of code compilation.
- [Decompiled .NET assemblies](https://source.dot.net/) - Browse the decompiled source code of .NET libraries.
- [Microsoft Testing Platform](https://learn.microsoft.com/en-us/dotnet/core/testing/microsoft-testing-platform-intro?tabs=dotnetcli)
- [.NET youtube channel](https://www.youtube.com/@dotnet)
