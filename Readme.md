1. Download and install .NET 5.0 SDK (preview) https://dotnet.microsoft.com/download/dotnet/5.0
2. Choose OS you want to create single file for (in `.csproj` element `<RuntimeIdentifier>`) currently set to Linux
3. Publish in release mode `dotnet publish -c Release`

Should restore, build and publish the `gui` executable to `bin/Release/net5.0/linux-x64/publish`

