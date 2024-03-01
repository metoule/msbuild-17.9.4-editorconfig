# msbuild-17.9.4-editorconfig
Dummy project using `.editorconfig`. 

With .NET SDK 8.0.101, IDE0036 is correctly reported by `dotnet build`, but it's not reported with .NET SDK 8.0.200.

With MSBuild 17.8.3:

![image](https://github.com/metoule/msbuild-17.9.4-editorconfig/assets/24547430/7e3ceca5-4703-4e17-ad7f-e96d470e4563)


With MSBuild 17.9.4:

![image](https://github.com/metoule/msbuild-17.9.4-editorconfig/assets/24547430/07f91e52-f067-4542-944b-376d0a72c6a1)
