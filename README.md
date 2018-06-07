## Xamarin University course content templates

These are a series of `dotnet new` templates for generating course content for the Xamarin University self-guided learning portal.

### Get started

#### Prerequisites

These templates use the `dotnet new` functionality of the .NET Core SDK. If you don't already have it installed (via the Visual Studio installer, for instance), [download and install the latest .NET Core SDK](https://www.microsoft.com/net/learn/get-started/).

#### Install the templates via NuGet package

These templates are published to NuGet for simple installation using the .NET tooling. The following command will install and make them available for use with the `dotnet new` command-line system.

```bash
dotnet new --install XamarinUniversity.ContentTemplates
```

To uninstall the templates, use the same command but with the `--uninstall` option.

```bash
dotnet new --uninstall XamarinUniversity.ContentTemplates
```

#### Install the templates locally

If you are working with a local copy of these templates, run the following command to install them.

```bash
dotnet new --install /path/to/templates/directory/
```

While installing templates with that command can be done from a relative path (e.g., `--install ./templates/directory/`), uninstalling locally-installed templates seems to prefer an absolute path.

```bash
dotnet new --uninstall /path/to/templates/directory/
```

### Current templates

For help with any of the parameters used in these templates, append `--help` to any template command.

```bash
dotnet new {template} --help
```

#### Course

Create the initial structure of a new course. There are many customizable parameters, but placeholder data you can replace manually is used by default.

```bash
dotnet new xamu-course
```

#### Objective

Create the initial structure of a course objective. There are several customizable parameters, but placeholder data you can replace manually is used by default.

```bash
dotnet new xamu-objective --name 1-do-something-cool
```

#### Exercise

Create the initial structure of a course exercise.

```bash
dotnet new xamu-exercise --name exercise2 --id abc123 --num 2 --title \"Create an exercise\" --repo \"https://github.com/XamarinUniversity/ABC101\" --goal \"In this exercise you will create an exercise.\" --summary \"In this exercise you created an exercise.\"
```

#### Page

Create a new course content page with the basic YAML, including a unique page GUID.

```bash
dotnet new xamu-page --page 1-create-a-page.md
```

### Future templates/features

* Content track (e.g., iOS, Android, Azure)
* Course quiz and other interactive element templates
* Markdown format helper
