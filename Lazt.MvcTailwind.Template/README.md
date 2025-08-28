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

## Installing the Template

Install the template directly from NuGet:

```bash
dotnet new install Lazt.MvcTailwind.Template::1.0.1
```

Verify installation:

```bash
dotnet new list
```

You should see:

```plaintext
Template Name       Short Name    Language    Tags
----------------    ------------  ----------  ----------------
MVC con Tailwind    mvclazt       [C#]        Web/MVC/Tailwind
```

---

## Creating a New Project

1. Create a project from the template:

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

Run the application with hot reload:

```bash
dotnet watch run
```

Open your browser at (port may vary):

```
https://localhost:5001
```

---

## Notes

- The template includes a ready-to-use MVC structure (`Controllers/`, `Views/`, `wwwroot/`) with TailwindCSS configured.
- TailwindCSS builds automatically when running `dotnet watch run`.
- If you notice that some styles are not being applied, try rebuilding the project or clearing your browser cache.

---

## License

This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
