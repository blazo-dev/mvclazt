# Lazt.MvcTailwind.Template

This repository contains an **ASP.NET MVC template integrated with TailwindCSS** for fast project scaffolding. It can be installed locally or published as a NuGet package.

---

## Features

- Pre-configured ASP.NET MVC structure
- TailwindCSS ready-to-use for styling
- Sample HomeController and views
- Supports `dotnet new` installation as a template
- Includes license and README for NuGet

---

## Requirements

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [Node.js](https://nodejs.org/) and npm

Optional:

- Visual Studio 2022 / VS Code
- Git

---

## Installing the Template

```bash
# Install from local nupkg
dotnet new install ./Lazt.MvcTailwind.Template.1.0.0.nupkg

# Verify installation
dotnet new list
````

---

## Creating a New Project

```bash
dotnet new mvclazt -n MyApp
cd MyApp
npm install
npm run css:build
dotnet run
```

Navigate to `https://localhost:5001` to see the app running, port may vary.

---

## Contributing

You can fork this repo and update the template or Tailwind setup as needed. Make sure to update the version in `.csproj` when publishing a new NuGet package.

---

## License

MIT License. See [LICENSE.txt](LICENSE.txt) for details.
