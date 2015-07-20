# AddLight
This plugin allow server admin to add invisible light sources.

Enable the plugin using the command **/AddLight enable** then left click any item or inside a WorldEdit selection with glowstone dust to add invisible light source.
You can also remove the light source by right clicking.

####Depedency:
AddLight depend on [LightAPI](https://www.spigotmc.org/resources/lightapi.4510/) from BeYkeRYkt.

####Commands:
* /AddLight help : Display AddLight help
* /AddLight [enable|on] : Enable light creation
* /AddLight [disable|off] : Disable light creation
* /AddLight <number> : Define light intensity (1-15)
* /AddLight ConnectedBlocks : Create lights to all connected blocks (be very carreful)

####Permissions:
* AddLight.admin : Allows creation of light to admin users
* AddLight.user : Allows creation of light to any users
* AddLight.use : Allows a user to use this plugin
* AddLight.worldedit : AddLight can apply to a WorldEditSelection
* AddLight.connected : AddLight can apply to any connected blocks
* AddLight.intensity : user can change the light intensity

* AddLight.* : given to op
  * AddLight.admin

* AddLight.admin
  * AddLight.use
  * AddLight.worldedit
  * AddLight.connected
  * AddLight.intensity

* AddLight.user
  * AddLight.use

####Config:
The plugin use metrics and an integrated updater.<br>Both can be disable in config.yml
