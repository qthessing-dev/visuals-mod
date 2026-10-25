# Visuals (Fabric, MC 1.21.11, Yarn)

Complete Fabric project. With Java 21 and Gradle 9.x installed:

    gradle wrapper
    ./gradlew build

(Windows: gradlew.bat build.) The mod jar is build/libs/visuals-1.0.0.jar (not the -sources jar).
Put it in your mods folder with Fabric API for 1.21.11.

If Gradle says a version doesn't exist, check fabricmc.net/develop for 1.21.11 and edit gradle.properties
(fabric_version is the one most likely to need changing).

Keys: G = Fullbright, H = Player ESP, K = Freecam (WASD, Space up, Shift down, Ctrl faster) (rebind in Controls).

## No local setup? Build it on GitHub
Create a free GitHub account, make a new repo, upload everything in this folder (including the hidden .github folder),
open the Actions tab, run "build", then download the "visuals-jar" artifact. The jar inside is the mod.
