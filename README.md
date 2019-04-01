## Electron.NET

```bash
npm install electron-packager --global
dotnet tool install ElectronNET.CLI -g

dotnet new webapi --language C# --output src/ElectronNet
electronize init

dotnet add src/ElectronNet/ElectronNet.csproj package  ElectronNET.API
```