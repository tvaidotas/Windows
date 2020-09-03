# Windows

## Windows update

Services -> Windows update -> Stop

Services -> Windows update -> Properties -> Disabled

## Notifications

Notifications & actions -> Disable everything 

## Quick access in File explorer

[download](https://blog.techinline.com/2018/11/30/how-to-disable-quick-access-in-windows-10-file-explorer/)

## Windows bloatware

Use [10appsmanager](https://www.thewindowsclub.com/10appsmanager-windows-10) to get rid of bloatware

## Power Toys

[download](https://github.com/microsoft/PowerToys)

Need .net core 3.1 [download](https://dotnet.microsoft.com/download/dotnet-core/thank-you/sdk-3.1.401-windows-x64-installer)

Open powershell as Administrator

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`

`choco install powertoys` 

### Configuration

General -> Always run as administrator
General -> Dark theme
General -> Run at startup

Shortcut guide -> press duration -> 500

## Drivers

* Chipset drivers
* Command centre
* Gaming app
* Intel network wt
* Live update
* X Boost

Link to motherboard [drivers](https://www.msi.com/Motherboard/support/X370-GAMING-PRO-CARBON)

[download]()

## Winrar

[download](https://www.rarlab.com/download.htm)

## Git

[download](https://git-scm.com/downloads)

`
git config --global user.name
git config --global user.email
`

## Intellij

[download](https://www.jetbrains.com/idea/download/#section=windows)

### Assign more RAM

In the `idea64.exe.vmoptions` file

-Xms2048m
-Xmx4096m

### Enable mouse wheel zoom

Settings -> Editor -> General

### Plugins

* Material theme UI
* Atom Material icons
* Nyan progress bar

### Disable project re-opening

Appearance & Behaviour -> System Settings

### Github account

Settings -> Version Control -> GitHub

## Avast

[download](https://www.avast.com/en-gb/free-antivirus-download#pc)

## GeForce Experience

[download](https://www.nvidia.com/en-gb/geforce/geforce-experience/)

## Greenshot

[download](https://getgreenshot.org/downloads/)

## Java (JDK/JRE)

[download](https://www.oracle.com/uk/java/technologies/javase/javase-jdk8-downloads.html)

Set the JAVA_HOME environment variable.

Add java /bin directory to the path. 

## Maven

[download](https://maven.apache.org/download.cgi)

Set MAVEN_HOME environment variable.

## Office 365

[download]()

## Teams

[download](https://www.microsoft.com/en-gb/microsoft-365/microsoft-teams/download-app)

## ICue

[download](https://www.corsair.com/ww/en/downloads)

## Steelseries

[download](https://steelseries.com/engine/post-download)

## Discord

[download](https://discord.com/download)

## Obs

[download](https://obsproject.com/welcome)

## Virtual box

[download](https://www.virtualbox.org/wiki/Downloads)

## Nord

[download](https://nordvpn.com/download/windows/)

## Postman

[download](https://www.postman.com/downloads/)

## Spotify

[download](https://www.spotify.com/uk/download/other/)

## Sublime

[download](https://www.sublimetext.com/3)

## Teamviewer

[download](https://www.teamviewer.com/en/download/windows/)

## Adobe reader

[download](https://get.adobe.com/uk/reader/)

## VLC

[download](https://get.videolan.org/vlc/3.0.11/win32/vlc-3.0.11-win32.exe)

## Utorrent

[download](https://www.utorrent.com/downloads/complete/track/stable/os/win)

## Calibre

[download](https://calibre-ebook.com/download_windows)

## Python SDK

[download](https://www.python.org/downloads/)

## PyCharm

[download](https://www.jetbrains.com/pycharm/download/#section=windows)

In the `pycharm64.exe.vmoptions` file

-Xms2048m
-Xmx4096m

## Steam

[download](https://store.steampowered.com/about/)

## Battlenet

[download](https://www.blizzard.com/en-sg/apps/battle.net/desktop)

## Epic store

[download](https://www.epicgames.com/store/en-US/download)

## Runelite

[download](https://runelite.net/)