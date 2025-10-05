***

## 📜 Update Log

<details>
<summary>Click to view version history</summary>

### Version 0.2V

-   **Friendly Fire**: A toggle has been added to the main menu to enable or disable friendly fire. The damage application logic has been patched to respect this setting.
-   **Time Control**: Only the host can now control the game speed. If the host dies, control is automatically transferred to the next living player.
-   **Respawning**: A system has been implemented to respawn dead players when moving to the next layer. Players who died on the previous level will respawn with damaged body parts.
-   **Console Access**: The console is now restricted to the host by default. The host can grant and revoke console access to other players using new console commands: `grantconsole <playerid>` and `revokeconsole <playerid>`.
-   **Tutorial**: The multiplayer mod is now disabled during the tutorial scene.
-   **Spawn Options**: A setting has been added to the main menu to allow players to choose between spawning in a single pod or separate pods.
-   **Code Locality**: Patches have been reviewed to ensure that UI, camera, and other local effects are not unnecessarily synchronized across the network.
-   **Game Modes**: The mod is now compatible with the "Unchipped" and "RadiationLine" game modes.

</details>

***
