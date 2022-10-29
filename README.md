# InfinityClient
[![Discord](https://img.shields.io/badge/chat-on%20discord-brightgreen.svg)](https://discord.gg/P3YvxxE5Dt)

## A 1.16.5 Minecraft utility mod for bypass.

## Installing

InfinityClient is a forge mod. Download the [latest release](#downloading), or preferably, [**build it yourself**](#building). 

Download and run the installer for Forge from [here](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.16.5.html).

Move the InfinityClient jar file to the `mods` folder in your `.minecraft` directory.

## Usage

While ingame, press <kbd>Y</kbd> to open the GUI. The wizard will help you further. He doesn't bite.

The command prefix is `.` by default. The autocompletion will list what commands are available.

## Troubleshooting
If you encounter bugs or crashes, please [open a new issue](../../issues/new/choose).

To ask for help, join the [Discord](https://discord.gg/P3YvxxE5Dt).

## Downloading

Note: You need to be logged into GitHub to do this. If you don't want to login, [build](#building) your own jar, or download the latest from [releases](https://github.com/Arthur8959/InfinityClient/releases/latest). 

1. Go to the [Actions](https://github.com/Arthur8959/InfinityClient/actions) tab
2. Click on the latest action
3. Click on "Infinity Client Artifacts archive"
4. Extract downloaded zip file
5. [Install](#installing)

If you get a 404 error after following step 3, you're not logged in to GitHub.

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
