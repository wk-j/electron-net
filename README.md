## Electron.NET

Install tool

```bash
npm install electron-packager --global
dotnet tool install ElectronNET.CLI -g
```

Create project

```bash
dotnet new webapi --language C# --output src/ElectronNet
dotnet add src/ElectronNet/ElectronNet.csproj package  ElectronNET.API
electronize init src/ElectronNet
```

Start

```bash
npm install
npm run parcel-watch

cd src/ElectronNet
electronize start
```