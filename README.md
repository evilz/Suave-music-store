# Suave-music-store 
Code from https://theimowski.gitbooks.io/suave-music-store 

Project init
------------

```
dotnet new console -lang f# -n suave-music-store
dotnet add suave-music-store package suave
cd suave-music-store
dotnet run
```

Add watch

```xml
<ItemGroup>
  <DotNetCliToolReference Include="Microsoft.DotNet.Watcher.Tools" Version="1.0.0" />
</ItemGroup> 
```
then
```
dotnet restore
dotnet watch run
```
