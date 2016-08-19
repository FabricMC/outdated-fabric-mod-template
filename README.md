# fabric-mod-template
A template for simple Fabric mods.

## Setup
In the `gradle.properties` file, change the `group` and `archivesBaseName` to their appropriate values. Generally, the group is a reverse domain name (e.g. `com.example`), if you don't own a domain name it is acceptable to use your own name for the group. The `archivesBaseName` is the name of your mod. 

You should also change the `mc_version` and `fabric_version` properties to the latest Minecraft and Fabric versions.

In the `mod.json` file in `src/main/resources`, you should change the `id` and `group` properties to match the ones you used in your `gradle.properties` file.

In the `mod.json` file, the `modClass` property is the fully qualified name of your main mod class. You should change the property (and rename the class itself) to be part of your mod package.

## IDEA
1. Run the `setupFabric` task.
2. Run the `genIdeaRuns` task.
3. Open the result `.ipr` file in IDEA.