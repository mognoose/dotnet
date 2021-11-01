# Dotnet kehitysympäristön asennus

## VScode plugari
Asenna vscodeen C# plugari.
Ctrl+P ja liitä alla oleva koodi
```
ext install ms-dotnettools.csharp
```

## Dotnet CLI
Lataa microsoft repository
```
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
```
Asenna repo
```
sudo apt install ./packages-microsoft-prod.deb
```
Päivitä repo ja asenna CLI
```
sudo apt update && sudo apt install dotnet-sdk-5.0
```
## Luo uusi projekti
Luo uusi kansio ja luo sinne uusi projekti
```
dotnet new console
```
Projekti käynnistetään komennolla
```
dotnet run
```
### Lähde
https://ubuntu.com/blog/creating-cross-platform-applications-with-net-on-ubuntu-on-wsl