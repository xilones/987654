987654
======

>16:57:42 [INFO] [JSONAPI] Enabling JSONAPI v4.3.6 >16:57:42 [SEVERE] java.lang.NoClassDefFoundError: net/minecraft/server/v1_5_R3/Packet >16:57:42 [SEVERE] at java.lang.ClassLoader.defineClass1(Native Method) >16:57:42 [SEVERE] at java.lang.ClassLoader.defineClass(ClassLoader.java:787) >16:57:42 [SEVERE] at java.security.SecureClassLoader.defineClass(SecureClassLoader.java:142) >16:57:42 [SEVERE] at java.net.URLClassLoader.defineClass(URLClassLoader.java:447) >16:57:42 [SEVERE] at java.net.URLClassLoader.access$100(URLClassLoader.java:71) >16:57:42 [SEVERE] at java.net.URLClassLoader$1.run(URLClassLoader.java:361) >16:57:42 [SEVERE] at java.net.URLClassLoader$1.run(URLClassLoader.java:355) >16:57:42 [SEVERE] at java.security.AccessController.doPrivileged(Native Method) >16:57:42 [SEVERE] at java.net.URLClassLoader.findClass(URLClassLoader.java:354) >16:57:42 [SEVERE] at org.bukkit.plugin.java.PluginClassLoader.findClass0(PluginClassLoader.java:80) >16:57:42 [SEVERE] at org.bukkit.plugin.java.JavaPluginLoader.getClassByName0(JavaPluginLoader.java:300) >16:57:42 [SEVERE] at org.bukkit.plugin.java.PluginClassLoader.findClass0(PluginClassLoader.java:76) >16:57:42 [SEVERE] at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:53) >16:57:42 [SEVERE] at java.lang.ClassLoader.loadClass(ClassLoader.java:423) >16:57:42 [SEVERE] at java.lang.ClassLoader.loadClass(ClassLoader.java:356) >16:57:42 [SEVERE] at com.alecgorge.minecraft.jsonapi.JSONAPI.onEnable(JSONAPI.java:186) >16:57:42 [SEVERE] at org.bukkit.plugin.java.JavaPlugin.setEnabled(JavaPlugin.java:217) >16:57:42 [SEVERE] at org.bukkit.plugin.java.JavaPluginLoader.enablePlugin(JavaPluginLoader.java:457) >16:57:42 [SEVERE] at org.bukkit.plugin.SimplePluginManager.enablePlugin(SimplePluginManager.java:381) >16:57:42 [SEVERE] at org.bukkit.craftbukkit.v1_6_R2.CraftServer.loadPlugin(CraftServer.java:282) >16:57:42 [SEVERE] at org.bukkit.craftbukkit.v1_6_R2.CraftServer.enablePlugins(CraftServer.java:264) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.MinecraftServer.l(MinecraftServer.java:313) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.MinecraftServer.f(MinecraftServer.java:290) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.MinecraftServer.a(MinecraftServer.java:250) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.DedicatedServer.init(DedicatedServer.java:151) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.MinecraftServer.run(MinecraftServer.java:391) >16:57:42 [SEVERE] at net.minecraft.server.v1_6_R2.ThreadServerApplication.run(SourceFile:582) >16:57:42 [SEVERE] Caused by: java.lang.ClassNotFoundException: net.minecraft.server.v1_5_R3.Packet >16:57:42 [SEVERE] at org.bukkit.plugin.java.PluginClassLoader.findClass0(PluginClassLoader.java:70) >16:57:42 [SEVERE] at org.bukkit.plugin.java.PluginClassLoader.findClass(PluginClassLoader.java:53) >16:57:42 [SEVERE] at java.lang.ClassLoader.loadClass(ClassLoader.java:423) >16:57:42 [SEVERE] at java.lang.ClassLoader.loadClass(ClassLoader.java:356) >16:57:42 [SEVERE] ... 27 more >16:57:42 [SEVERE] Couldn't register my Packet71WeatherProxy! Is BukkitForge/Bukkit up to date with JSONAPI?
