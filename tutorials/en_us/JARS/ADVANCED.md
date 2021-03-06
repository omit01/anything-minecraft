# Advanced JAR picking

If you want to go a little more in-depth with JAR picking, you've come to the right place.
Most popular Spigot/Bukkit JARs are :

- [PaperMC](https://papermc.io/) - Most popular JAR for Spigot/Bukkit, quite fast and stable, they roll out small patches at least every 2 days or so, good choice if you're just starting with your MC server and don't have much past experience because it's fast and simple. Most if not all spigot plugins work with this JAR.
  starting with your MC server and don't have much past experience because it's fast and simple.
- [Spigot](https://www.spigotmc.org/) - Original fork of Bukkit, improved performance vs CraftBukkit, still widely used, seems to be harder for newbies to download because it links to Jenkins,
  which may look confusing to them and they don't know where to click, recommended alternative if for some reason you don't want to use PaperSpigot.
- [CraftBukkit](https://getbukkit.org/download/craftbukkit) - It's the BASE for all forks that are out today and they still are updating it to this day, not newbie friendly
  at all because it requires manual building and doesn't provide an already built JAR (exception is if you use your host to give you JARs).
- [Purpur](https://purpur.pl3x.net/) - It's a fork of both PaperSpigot and Tuinity to deliver very fast performance with stability (and good performance)
  for high player counts and it adds a lot of custom features that aren't seen on any other forks.
  (I'll have to try it out one day, seems quite interesting)
- [Tuinity](https://github.com/Spottedleaf/Tuinity) - PaperMC fork aimed at improving stability and performance at high player counts, also never heard of it, by description it seems to be exact same
  performs as PaperSpigot except at the high player counts.

---

Most popular network JARs:

- [BungeeCord](https://www.spigotmc.org/wiki/bungeecord/) - Base for the Waterfall fork, these JARs are used for configuring networks of which an example is Hypixel or Mineplex, it is used for distributing
  workload and players to different lobbies (are actually different server instances run with seperate files and data).
  No, this can't be used as a normal JAR and requires at least 3 servers/instances, one is BungeeCord (or it's fork) which is called the proxy, players
  connect to this proxy and are sent to the default server which is set in config. Let's say server "Lobby" is default, it will send you there,
  after that you can connect to another server, for example "Survival" which is running in a seperate server/instance and BungeeCord enables the functionality
  travel across these different servers without returning back to the multiplayer menu screen.
  (It can be done with special plugins which utilize BungeeCord API to send you to the chosen server on click, you'll most commonly see it as the
  compass or a portal)

- [Waterfall](https://papermc.io/downloads#Waterfall) - Fork of BungeeCord, faster than BungeeCord and has general improvements and tweaks which make it the more preferred network JAR, works basically the
  same as BungeeCord (talking about the use, it doesn't have a different system).
  [Velocity](https://velocitypowered.com/) - A next-generation Minecraft proxy focused on scalability and flexibility. It allows server owners to link together multiple Minecraft servers so they may appear as one.

- [Travertine](https://github.com/PaperMC/Travertine) - Fork of Waterfall with added 1.7.10 support if you want that old school experience ;)

---

Most popular modded server JARs: 1. Forge 2. Fabric (I've never run a modded server, little to no experience with them)

- [Forge](http://files.minecraftforge.net/) - Most popular JAR for either client or server-side use, has the widest mod support. Running a forge server will require the same mods to be used by both the client
  and the server and will refuse connection if there are mod incompatibilities. Dedicating more ram is recommended or even having a dedicated machine to running a
  modded server is recommended.
- [Fabric](https://fabricmc.net/) - Faster than Forge, doesn't run Forge mods and has lesser mod support

---

Extras:

Sponge - Enables use of mods and plugins which are made for Sponge, makes your server extra spicy if you know how to do it right!
ore.spongepowered.org | The place to get the plugins (has LuckPerms :O)
