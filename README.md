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

#### Course

Create the initial structure of a new course.

### Future templates/features

* Course exercise template
* Course objective template
* Course quiz and other interactive element templates
* Auto-complete helper
