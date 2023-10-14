# Minecraft optimized configs

### This repo is based on this guide by [YouHaveTrouble](https://github.com/YouHaveTrouble/minecraft-optimization). All of the credit belong to them.

#### Then whats this repository is for?

This repository is for people who need optimized configs without going through the hassle of reading and understanding the extensive guide i.e this is for **lazy people**.  
You can freely use this configs in your servers without any restrictions. There are no credits or any sorts of names added in the configs.  

## More about this repository

### Whats new here?

- contains actual config files to easily download and use them.  
- has a configured anti-Xray module in `paper-world-defaults.yml` for overworld and nether.

### Values to change or tweak:

Change these following options to suite your needs  

server.properties  

- `view-distance`
- `simulation-distance`
- `online-mode`
- `difficulty`
- `max-players`

## Software usage  

### Recommended server software

#### Plugins:
- [Purpur](https://purpurmc.org)- Purpur is a fork of Pufferfish thats focused on performance and customization in Minecraft servers. The file to edit for all the options is `purpur.yml`.  
- [Paper](https://papermc.io)- Paper is a fork of Spigot mostly focused on bug fixes and performance improvements. Works with all plugins. The files to edit are `paper-global.yml` and `paper-world-defaults.yml`.

#### Mods:
- [Fabric](https://fabricmc.net)- Lighweight mod loader for minecraft servers that preserves the vanilla experience of the game. It also is the best one for clients due to various performance mods it offers.

## Tips 101

### If you are running your minecraft server on a free host(Aternos,Falixnodes,Minehut etc.) then you should do the following (*i know you guys broke xD*):
- **Pregen your world**- Free hosts typically have 1 or 2 threads allocated to a server for which you dont get the best performance. To prevent overloading of your server when someone loads chunks while travelling, you should pregenerate your worlds. This way your server dont need to do extra work for generating new chunks. You can pregen using these plugins [Chunky](https://www.spigotmc.org/resources/chunky.81534/) and [FCP](https://www.spigotmc.org/resources/fast-chunk-pregenerator.74429/).
- **Dont use cracked plugins**- You should never use cracked plugins aka plugins that are paid  but available on illegal sites(blackspigot,spigotunlocked etc). They often contain malware and backdoors which have serious effect on your server. Your server files and personal info are at risk. Always download plugins from verified/official sites. In case of malware infection or backdoor, delete all the jars files and make a new server if possible.
- **Take backups**- Backups are very important for keeping your server data safe. In case of data corruption or having to rollback cause of exploits or other reasons, backups is your messiah. You can do manual backups on your PC(recommended) or use a plugin to do it. [DrivebackupV2](https://www.spigotmc.org/resources/drivebackupv2.79519/) is a plugin that can do automated backups to Google Drive, OneDrive, Dropbox or FTP/SFTP server.

### Administration

- Lag measuring- Lag is mainly determined by mspt(milliseconds per tick). You should use tools like [Spark](https://spark.lucko.me) to investigate. Read Spark's documentation for more info.  
In spark, the command `/spark tps` shows TPS(ticks per second) and Tick durations of the server. The main values to look into are:  
`Tick durations- min,95%tile and max`  
If these three values are in green then the server is not lagging. Lower the number the better the server is performing. Anything above 50 mspt means the server is struggling.

## Useful links

[Minecraft Wiki](https://minecraft.wiki)  
[SpigotMC](https://www.spigotmc.org)  
[PaperMC](https://papermc.io)  
[FabricMC](https://fabricmc.net)  
[CurseForge](https://www.curseforge.com) 

## Free Minecraft hosts  

[Aternos](https://aternos.org/:en/)  
[Falixnodes](https://falixnodes.net)


## Appreciation

If you like the content of the repository, consider starring the repo. Thanks in advance!! 🤗  
If you face any issues with the configs or find anything broken, feel free to open an issue and i will try to solve the issue. Since the guide is not my original work, i will try my best to communicate the issue to the original author.
