## Waila (What Am I Looking At)
This is a copy of ProfMobius' Minecraft mod [Waila](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289765-waila-1-5-2).

This code is from the [forge_965_bugfixing](https://bitbucket.org/ProfMobius/waila/src/db53ba213fdbb5ed87ab8db70c9bfdaa2f569f33/?at=forge_965_bugfixing) branch of the main repository. It was added after the latest 1.6.4 release of Waila (1.5.2a) to fix the dependency on ModLoader introduced in 1.5.2.

I've moved the code into a ForgeGradle structure to make it easier to build.

The intent of this repository is to provide a copy of Waila for 1.6.4 that you can successfully compile your mod against, it's not intended for regular use.

## Setting up Forge Gradle
To set up Forge Gradle, run `gradlew setupDecompWorkspace`.

To generate an IDE project, run `gradlew eclipse` (for Eclipse) or `gradlew idea` (for IntelliJ IDEA).

## Building
Place CodeChickenLib-dev-1.6.4-1.0.0.62.jar (from [files.minecraftforge.net](http://files.minecraftforge.net/CodeChickenLib/index_legacy.html)) in the libs folder and run `gradlew jar`.