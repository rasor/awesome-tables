## Awesome CLI - on Windows

### Chocolatey

On Windows some tools can be troublesome to install correct.  
To deal with that matter the tool Chocolatey uses Powershell to make workarounds that makes the tool being installed in a more troubleless way.  
This could for instance be setting some environment variables which supports the program in Windows.  

Install [Chocolatey](https://chocolatey.org/install) from CMD with this command:

´´´bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

# Verify install:
choco -v
# 0.10.11
´´´

## Tools

With Chocolatey installed you can use the tool to install other tools.  

|CLI|Cmd|Category|choco install|As Admin|
|---|---|---|---|---|
|jq|[jq](https://stedolan.github.io/jq/manual/)|Data Transform|jq|y|
|yarn|[yarn](https://yarnpkg.com/en/docs/cli/)|Package Mgr|yarn||

Some installation examples

´´´bash
choco install jq
# Chocolatey v0.10.11
# Chocolatey installed 1/1 packages.
jq -V
# jq-1.5

npm -v # yarn checks for npm
# 6.1.0
choco install yarn
yarn -v
#1.1.0
´´´

## Links

* [Using NVM for Windows and Yarn](https://rasor.github.io/using-nvm-for-windows-and-yarn.html)

The End
