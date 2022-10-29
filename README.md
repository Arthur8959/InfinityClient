# InfinityClient
[![Discord](https://img.shields.io/badge/chat-on%20discord-brightgreen.svg)](https://discord.gg/P3YvxxE5Dt)

## A 1.12.2 Minecraft utility mod for bypass.

## Installing

InfinityClient is a forge mod. Download the [latest release](#downloading). 

Download and run the installer for Forge from [here](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html).

Move the InfinityClient jar file to the `mods` folder in your `.minecraft` directory.

## Usage

While ingame, press <kbd>Y</kbd> to open the GUI. The wizard will help you further. He doesn't bite.

The command prefix is `.` by default. The autocompletion will list what commands are available.

## Troubleshooting
If you encounter bugs or crashes, please [open a new issue](../../issues/new/choose).

To ask for help, join the [Discord](https://discord.gg/P3YvxxE5Dt).

## Downloading

Note: You need to be logged into GitHub to do this. If you don't want to login, [build](#building) your own jar, or download the latest from [releases](https://github.com/Arthur8959/InfinityClient/releases/latest). 

1. Install forge 1.12.2
2. Open the .zip and extract to the desktop all files
3. Open Infinity-Loader for get requirements
3. Move InfinityClient b9.jar to your mod folder in your .minecraft folder
4. Launch Minecraft

<details>
 <summary>Images</summary>

 ![downloading](.github/IMAGES/downloading.png)

</details>
## Setting up

### IntelliJ
1. In Intellij, navigate to `File > New > Project from Version Control...`
2. Paste `https://github.com/Arthur8959/InfinityClient/` in the `URL` field, and hit **Clone**.
3. Allow gradle to set up the project. This might take a while. *(~ 8 minutes)*

###### Optionally,
* To generate the run configurations, run the `idea` gradle task.
* To generate attachable sources, run the `genSources` task and attach the generated sources in your IDE.

## Building

1. Download or clone the InfinityClient repository.
2. Run `gradle build`
3. The built jar is in `build/libs/`. There are 2 jars, pick the in the format of `InfinityClient-version.jar`, not `InfinityClient-version-shadow.jar`.


## Thank you

The [Minecraft Forge team](https://github.com/MinecraftForge) for [Forge](https://files.minecraftforge.net/)
