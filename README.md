LykoClient v1.1






Obama approved Minecraft utility mod built for Fabric 1.18 and 1.19.
Packed with PvP, render, movement, and QoL modules.


🎮 Showcase
<details> <summary>Images</summary>

</details>
🛠️ Installation
For normal users

Follow the instructions on the Downloads Page.
For 200 IQ developers

    Clone or download the branch for your desired version.

    Open a terminal or command prompt in the main project folder.

    Run the setup for your IDE below:

Eclipse

Windows:

gradlew genSources eclipse

Linux/macOS:

chmod +x ./gradlew  
./gradlew genSources eclipse

Then in Eclipse:
File > Import > Gradle > Existing Gradle Project → Select root folder.

IntelliJ IDEA

Windows:

gradlew genIdeaWorkspace

Linux/macOS:

chmod +x ./gradlew  
./gradlew genIdeaWorkspace

In IntelliJ:
File > Open → Select build.gradle → Open as Project.

Other IDEs
Use the Fabric setup guide: FabricMC Wiki

    💡 For older code (pre-1.17), use this commit and navigate to the correct version folder.

🔌 Recommended Mods

Compatible mods that work well with LykoClient (no Fabric API required):
Multiconnect or ViaFabric

Allows connecting to older or newer server versions from a single client.
Baritone

Powerful pathfinding bot for automation—mining, walking, building, etc.
Sodium, Lithium, Phosphor

Boosts performance and fixes rendering/lighting inefficiencies.
📜 License

If you distribute a modified version of LykoClient or reuse any of its features, you are required to:

    Disclose your source code

    Clearly document your changes

    Use a compatible open-source license

    Follow all terms in the LICENSE
