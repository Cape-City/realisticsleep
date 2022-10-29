![Realistic Sleep icon](docs/media/icon_128x128.png)

# Realistic Sleep

Makes sleeping speed up time instead of skipping to day.

![Realistic Sleep gif](docs/media/realistic_sleep.gif)

## Dependencies

- [Cloth Config API](https://modrinth.com/mod/cloth-config)

## Incompatibilities  

Any mods that add sleep voting, or otherwise modify the sleeping mechanic itself will not work with this mod (sleep voting already exists by design).  
Any mods which simply add buffs/debuffs after waking up should work.

## Recommended mods  

- ModMenu for an in game configuration screen (only for singleplayer/LAN)

## Download

[![github](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/cozy/available/github_vector.svg)](https://github.com/Steveplays28/pathunderfencegates)
[![modrinth](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/cozy/available/modrinth_vector.svg)](https://modrinth.com/mod/pathunderfencegates)
[![curseforge](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/cozy/available/curseforge_vector.svg)](https://www.curseforge.com/minecraft/mc-mods/pathunderfencegates)

![fabric](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/compact/supported/fabric_vector.svg)
![quilt](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/compact/supported/quilt_vector.svg)

Supports Minecraft versions 1.18-1.19.2.  
Made for the Fabric and Quilt modloaders.  
Server side only.

## FAQ

![forge](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@2/assets/cozy/unsupported/forge_vector.svg)

- Q: Will you be backporting this to lower Minecraft versions?  
A: No.

- Q: Forge pls?  
A: Also no.

- Q: Does this mod work in multiplayer?  
A: Yes! The speed of the night scales linearly for each player that's sleeping at the same time.

- Q: Does only the server need this mod or does the client need it too?  
A: Only the server needs this mod (but it works on the client too if you're going to host LAN or play singleplayer)

- Q: Can you still avoid rain/thunder by sleeping?  
A: Yes. After sleeping until dawn the weather will become clear. I might make this configurable in the future, let me know if you want this.

- Q: Does this mod speed up the block entities in loaded chunks like furnaces?  
A: Yes!

## License

This project is licensed under LGPLv2, see [LICENSE](https://github.com/Steveplays28/pathunderfencegates/blob/main/LICENSE).
