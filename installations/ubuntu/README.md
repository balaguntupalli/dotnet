# the below document to install dotnet 3.1

```
sudo apt-get update
sudo wget https://packages.microsoft.com/config/ubuntu/18.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt-get update
sudo apt-get install dotnet-sdk-3.1 -y
```
* to check all SDK installed
```
dotnet --list-sdks
output:
3.1.201 [/usr/share/dotnet/sdk]
```

* to list installed runtimes
```
dotnet --list-runtimes
output:
Microsoft.AspNetCore.App 3.1.3 [/usr/share/dotnet/shared/Microsoft.AspNetCore.App]
Microsoft.NETCore.App 3.1.3 [/usr/share/dotnet/shared/Microsoft.NETCore.App]
```


note: based on the output we know that .NEt and ASP.NET core 3.1 SDK and runtime installed successfully
