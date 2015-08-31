#Dev Environment - Windows

**Setting up a Dev Environment for Web Code on a Windows machine**

## Terminal

The Windows Command line **cmd.exe** tool is acceptable but other tools are likely to be better for workflow.

Windows Powershell is also an option but I've run into some minor issues with npm and PS.

Other tools allow emulation of the terminal with colors and other configurable options.

- [cmder](http://cmder.net/)
- [ConEmu](http://conemu.github.io/)


## Package Management or Downloads

### Chocolatey Package Manager
*Chocolatey is a package manager for Windows that makes installation of several tools much easier.*

1. Install [Chocolatey](https://chocolatey.org/).

#### Install Required Packages Using Chocolatey
1. `choco install nodejs`
1. `choco install git`
1. `choco install redis-64`
1. `choco install mongodb`

### Downloads (the old fashioned way)
- [NodeJS](https://nodejs.org/download/)
- [Git](https://git-scm.com/)
- [Redis](https://github.com/MSOpenTech/redis)
- [MongoDB](https://www.mongodb.org/downloads)

