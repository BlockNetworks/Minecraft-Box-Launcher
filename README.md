<img src="https://user-images.githubusercontent.com/37006668/75309971-71791f00-5807-11ea-9073-cc447354324f.png" width="200px" />

# The Minecraft Box
<!-- Badges -->
![Dependencies status](https://david-dm.org/lukechu10/Minecraft-Box-Launcher.svg)
![ESLint status](https://github.com/lukechu10/Minecraft-Box-Launcher/workflows/ESLint%20(Typescript)/badge.svg)
![Build status](https://github.com/lukechu10/Minecraft-Box-Launcher/workflows/Build%20binaries%20and%20package/badge.svg)
![Test](https://github.com/lukechu10/Minecraft-Box-Launcher/workflows/Test/badge.svg)
![GitHub All Releases](https://img.shields.io/github/downloads/lukechu10/Minecraft-Box-Launcher/total)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/lukechu10/Minecraft-Box-Launcher?label=latest%20pre-release)
![GitHub Language](https://img.shields.io/github/languages/top/lukechu10/Minecraft-Box-Launcher?color=rgb%288%2C144%2C166%29)

The **Minecraft Box** is a modern Minecraft launcher, designed to provide integrations with multiple Minecraft services, configurations and thirs party software. The launcher is made with web technologies including electronJS.

## Usage

```
git clone https://github.com/BlockNetworks/Minecraft-Box-Launcher
npm install
npm run prod
npm start
```

## Features
Symbol	| Meaning
-------	| -----------
✔	       | Availible in latest release / pre-release
🔨		| Work in Progress
🦄		| Planned
- Core
	- Create new game instances ✔
	- Instances are isolated from each other and do not share saves, settings or mods ✔
	- Official news feed from www.minecraft.net 🔨
- Authentication
	- Official Yggsdrasil Mojang Authentication ✔
	- Offline Mojang Authentication 🔨
	- Change skin inside launcher 🔨
	- View previous skins 🦄
- Install
	- Install vanilla releases, snapshots and historical versions ✔
	- Reinstall corrupted versions ✔
	- Can show installation progress ✔
	- Install forge directly from launcher 🦄
	- Install optifine directly from launcher 🦄
- Launch
	- Launch vanilla releases and snapshots ✔
	- Launch historical versions 🦄
	- Launch with forge 🦄
	- Launch with optifine 🦄
	- Custom jar 🔨
	- Launch offline 🔨
	- View log output ✔
- Java configuration
	- Custom java executable ✔
	- Custom java max and min memory ✔
	- Custom java arguments 🔨
- Instance configuration and management
	- Per-instance settings (seperate from global settings) 🔨
	- World saves manager (view and install maps) ✔ (partially)
	- Server manager ✔ (partially)
	- Mods manager (quickly view and install forge mods) 🦄
	- Install mod packs 🦄
	- Minecraft settings viewer 🦄
- Installed versions viewer (view which versions are installed and can be played) 🔨
- UI
	- Dashboard with widget system 🔨
		- Last played instance ✔
		- Mojang Account ✔
		- Hypixel related stats 🦄

## Contributing
See [CONTRIBUTING.md](https://github.com/lukechu10/Minecraft-Box-Launcher/blob/master/.github/CONTRIBUTING.md) for more details

Thanks for showing interest in this project. There is still a lot of work todo before the launcher is useful.

### Seting up your environment
Visual Studio Code is recommended for developping Minecraft Box.
You can also use www.gitpod.io, which is browser based and free for contributing with similar features:

[![Gitpod badge](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/lukechu10/Minecraft-Box-Launcher)

If for whatever reason non of these two options are availible, you can always use your favorite IDE.
All the commands are specified in `package.json` if you don't mind working with the command line.

### Submitting changes
Please send a GitHub Pull Request to Minecraft-Box-Launcher with a clear list of what you've done. 

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

```cmd
$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
```

Check out [CONTRIBUTING.md](https://github.com/lukechu10/Minecraft-Box-Launcher/blob/master/.github/CONTRIBUTING.md) for more details on how to contribute to this project.
