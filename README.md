# AppVeyor dotnet CLI bug [![Build status](https://ci.appveyor.com/api/projects/status/xklx740s41fqdqm2?svg=true)](https://ci.appveyor.com/project/bergmeister/appveyor-dotnetcli-bug)
REPRO to show that calling `dotnet new` commands such as e.g. `dotnet new mstest` or `dotnet new xunit` throw an error when being run in `AppVeyor`
