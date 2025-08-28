# MVC with Tailwind Template

A fully working ASP.NET MVC template integrated with TailwindCSS, ready to use as a starting point for new projects.

---

## Requirements

Before using this template, make sure you have installed:

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes with Node.js)

Optional but recommended:

- Visual Studio 2022 / VS Code
- Git (for version control)

---

## Installing the Template Locally

1. Navigate to the folder containing the `.nupkg` file:

```bash
cd path/to/Lazt.MvcTailwind.Template/nupkgs
````

2. Install the template locally:

```bash
dotnet new install ./Lazt.MvcTailwind.Template.1.0.0.nupkg
```

3. Verify the template is installed:

```bash
dotnet new list
```

You should see:

```
MVC with Tailwind (mvclazt)
```

---

## Creating a New Project

1. Create a new project using the template:

```bash
dotnet new mvclazt -n MyApp
cd MyApp
```

2. Install Node.js dependencies:

```bash
npm install
```

---

## Running the Project

1. Start the ASP.NET application:

```bash
dotnet run
```

2. Open your browser and navigate to, port may vary:

```
https://localhost:5001
```

---

## Notes

- The template includes a ready-to-use MVC structure (`Controllers/`, `Views/`, `wwwroot/`) with TailwindCSS configured.
- Any updates to TailwindCSS or npm packages should be done in `package.json` and rebuilt with `npm run css:build`.
- If you notice that some styles are not being applied, try rebuilding the project or clearing your browser cache.

---

## License

This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
