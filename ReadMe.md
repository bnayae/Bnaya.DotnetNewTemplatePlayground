# Creating a custom .NET CLI template

- [.NET SDK](https://github.com/dotnet/sdk/)
- [ASP.NET Core Template](https://github.com/dotnet/aspnetcore/blob/main/src/ProjectTemplates/Web.ProjectTemplates/content/WebApi-CSharp/.template.config/template.json)
- [Video Tutorial](https://www.google.com/search?q=Custom+templates+for+dotnet+new&oq=Custom+templates+for+dotnet+new&aqs=chrome..69i57j69i60.581j0j4&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:a6dbe0e2,vid:rdWZo5PD9Ek)*
- [Custom templates for dotnet new](https://learn.microsoft.com/en-us/dotnet/core/tools/custom-templates)
- [Tutorial: Create an item template](https://learn.microsoft.com/en-us/dotnet/core/tutorials/cli-templates-create-item-template)
- [Microsoft Templates](https://github.com/dotnet/templating)
- [WiKi](https://github.com/dotnet/templating/wiki)
- [Samples](https://github.com/dotnet/dotnet-template-samples)
- [Available Symbols Generators](https://github.com/dotnet/templating/wiki/Available-Symbols-Generators)
- [Template Schema](https://github.com/dotnet/templating/wiki/Reference-for-template.json)
- [Regex Switch](https://github.com/dotnet/templating/wiki/Available-Symbols-Generators#regex)

# Create the template

## Local

```bash
# dotnet build --force
dotnet pack -c Release --force -o .
dotnet new install . 
dotnet new uninstall .
```

## remote
```bash
dotnet new bnaya-cs-playground -h
```
