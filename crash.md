[08:15:40] [Client thread/INFO]: LWJGL Version: 2.9.4
[08:15:42] [Client thread/INFO] [STDOUT]: [net.minecraftforge.fml.client.SplashProgress:start:223]: ---- Minecraft Crash Report ----
// You're mean.

Time: 18-1-4 上午8:15
Description: Loading screen debug info

This is just a prompt for computer specs to be printed. THIS IS NOT A ERROR


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
    Minecraft Version: 1.10.2
    Operating System: Windows 10 (amd64) version 10.0
    Java Version: 1.8.0_151, Oracle Corporation
    Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
    Memory: 62576064 bytes (59 MB) / 267386880 bytes (255 MB) up to 2147483648 bytes (2048 MB)
    JVM Flags: 6 total; -XX:+UseG1GC -XX:-UseAdaptiveSizePolicy -XX:-OmitStackTraceInFastThrow -Xmn128m -Xmx2048m -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump
    IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
    FML: 
    Loaded coremods (and transformers): 
    GL info: ' Vendor: 'NVIDIA Corporation' Version: '4.5.0 NVIDIA 359.46' Renderer: 'GeForce GT 720M/PCIe/SSE2'
[08:15:43] [Client thread/INFO] [FML]: MinecraftForge v12.18.3.2511 Initialized
[08:15:43] [Client thread/INFO] [FML]: Replaced 231 ore recipes
[08:15:44] [Client thread/INFO] [FML]: Found 0 mods from the command line. Injecting into mod discoverer
[08:15:44] [Client thread/INFO] [FML]: Searching C:\Users\若冰\Desktop\MC-op\纯净版客户端\.minecraft\mods for mods
[08:15:44] [Client thread/INFO] [FML]: Also searching C:\Users\若冰\Desktop\MC-op\纯净版客户端\.minecraft\mods\1.10.2 for mods
[08:15:47] [Client thread/INFO] [FML]: Forge Mod Loader has identified 4 mods to load
[08:15:47] [Thread-6/INFO] [FML]: Using sync timing. 200 frames of Display.update took 274661899 nanos
[08:15:47] [Client thread/INFO] [FML]: Attempting connection with missing mods [mcp, FML, Forge, rabbitz] at CLIENT
[08:15:47] [Client thread/INFO] [FML]: Attempting connection with missing mods [mcp, FML, Forge, rabbitz] at SERVER
[08:15:48] [Client thread/ERROR] [FML]: An error occurred trying to load a proxy into {serverSide=Rabbitz.CommonProxy, clientSide=Rabbitz.ClientProxy}.net.hap.rabbitz.Rabbitz
java.lang.ClassNotFoundException: Rabbitz.ClientProxy
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:191) ~[launchwrapper-1.12.jar:?]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ModClassLoader.loadClass(ModClassLoader.java:75) ~[ModClassLoader.class:?]
    at java.lang.Class.forName0(Native Method) ~[?:1.8.0_151]
    at java.lang.Class.forName(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:71) [ProxyInjector.class:?]
    at net.minecraftforge.fml.common.FMLModContainer.constructMod(FMLModContainer.java:593) [FMLModContainer.class:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74) [guava-17.0.jar:?]
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.post(EventBus.java:275) [guava-17.0.jar:?]
    at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:243) [LoadController.class:?]
    at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:221) [LoadController.class:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74) [guava-17.0.jar:?]
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304) [guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.post(EventBus.java:275) [guava-17.0.jar:?]
    at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:145) [LoadController.class:?]
    at net.minecraftforge.fml.common.Loader.loadMods(Loader.java:559) [Loader.class:?]
    at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:220) [FMLClientHandler.class:?]
    at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:439) [bcx.class:?]
    at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:351) [bcx.class:?]
    at net.minecraft.client.main.Main.main(SourceFile:124) [Main.class:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at net.minecraft.launchwrapper.Launch.launch(Launch.java:135) [launchwrapper-1.12.jar:?]
    at net.minecraft.launchwrapper.Launch.main(Launch.java:28) [launchwrapper-1.12.jar:?]
Caused by: java.lang.NullPointerException
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:182) ~[launchwrapper-1.12.jar:?]
    ... 39 more
[08:15:48] [Client thread/ERROR] [FML]: Fatal errors were detected during the transition from CONSTRUCTING to PREINITIALIZATION. Loading cannot continue
[08:15:48] [Client thread/ERROR] [FML]: 
    States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
    UC    mcp{9.19} [Minecraft Coder Pack] (minecraft.jar) 
    UC    FML{8.0.99.99} [Forge Mod Loader] (forge-1.10.2-12.18.3.2511.jar) 
    UC    Forge{12.18.3.2511} [Minecraft Forge] (forge-1.10.2-12.18.3.2511.jar) 
    UE    rabbitz{1.0.0} [Rabbitz] (rabbitz.jar) 
[08:15:48] [Client thread/ERROR] [FML]: The following problems were captured during this phase
[08:15:48] [Client thread/ERROR] [FML]: Caught exception from Rabbitz (rabbitz)
net.minecraftforge.fml.common.LoaderException: java.lang.ClassNotFoundException: Rabbitz.ClientProxy

    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:88) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at net.minecraftforge.fml.common.FMLModContainer.constructMod(FMLModContainer.java:593) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.post(EventBus.java:275) ~[guava-17.0.jar:?]
    at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:243) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:221) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304) ~[guava-17.0.jar:?]
    at com.google.common.eventbus.EventBus.post(EventBus.java:275) ~[guava-17.0.jar:?]
    at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:145) [LoadController.class:?]
    at net.minecraftforge.fml.common.Loader.loadMods(Loader.java:559) [Loader.class:?]
    at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:220) [FMLClientHandler.class:?]
    at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:439) [bcx.class:?]
    at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:351) [bcx.class:?]
    at net.minecraft.client.main.Main.main(SourceFile:124) [Main.class:?]
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_151]
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source) ~[?:1.8.0_151]
    at java.lang.reflect.Method.invoke(Unknown Source) ~[?:1.8.0_151]
    at net.minecraft.launchwrapper.Launch.launch(Launch.java:135) [launchwrapper-1.12.jar:?]
    at net.minecraft.launchwrapper.Launch.main(Launch.java:28) [launchwrapper-1.12.jar:?]
Caused by: java.lang.ClassNotFoundException: Rabbitz.ClientProxy
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:191) ~[launchwrapper-1.12.jar:?]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ModClassLoader.loadClass(ModClassLoader.java:75) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at java.lang.Class.forName0(Native Method) ~[?:1.8.0_151]
    at java.lang.Class.forName(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:71) ~[forge-1.10.2-12.18.3.2511.jar:?]
    ... 33 more
Caused by: java.lang.NullPointerException
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:182) ~[launchwrapper-1.12.jar:?]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ModClassLoader.loadClass(ModClassLoader.java:75) ~[forge-1.10.2-12.18.3.2511.jar:?]
    at java.lang.Class.forName0(Native Method) ~[?:1.8.0_151]
    at java.lang.Class.forName(Unknown Source) ~[?:1.8.0_151]
    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:71) ~[forge-1.10.2-12.18.3.2511.jar:?]
    ... 33 more
[08:15:48] [Client thread/INFO] [STDOUT]: [net.minecraft.init.Bootstrap:func_179870_a:560]: ---- Minecraft Crash Report ----
// Why did you do that?

Time: 18-1-4 上午8:15
Description: There was a severe problem during mod loading that has caused the game to fail

net.minecraftforge.fml.common.LoaderExceptionModCrash: Caught exception from Rabbitz (rabbitz)
Caused by: net.minecraftforge.fml.common.LoaderException: java.lang.ClassNotFoundException: Rabbitz.ClientProxy
    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:88)
    at net.minecraftforge.fml.common.FMLModContainer.constructMod(FMLModContainer.java:593)
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
    at java.lang.reflect.Method.invoke(Unknown Source)
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
    at com.google.common.eventbus.EventBus.post(EventBus.java:275)
    at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:243)
    at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:221)
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
    at java.lang.reflect.Method.invoke(Unknown Source)
    at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
    at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
    at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
    at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
    at com.google.common.eventbus.EventBus.post(EventBus.java:275)
    at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:145)
    at net.minecraftforge.fml.common.Loader.loadMods(Loader.java:559)
    at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:220)
    at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:439)
    at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:351)
    at net.minecraft.client.main.Main.main(SourceFile:124)
    at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
    at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
    at java.lang.reflect.Method.invoke(Unknown Source)
    at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
    at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
Caused by: java.lang.ClassNotFoundException: Rabbitz.ClientProxy
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:191)
    at java.lang.ClassLoader.loadClass(Unknown Source)
    at java.lang.ClassLoader.loadClass(Unknown Source)
    at net.minecraftforge.fml.common.ModClassLoader.loadClass(ModClassLoader.java:75)
    at java.lang.Class.forName0(Native Method)
    at java.lang.Class.forName(Unknown Source)
    at net.minecraftforge.fml.common.ProxyInjector.inject(ProxyInjector.java:71)
    ... 33 more
Caused by: java.lang.NullPointerException
    at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:182)
    ... 39 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
    Minecraft Version: 1.10.2
    Operating System: Windows 10 (amd64) version 10.0
    Java Version: 1.8.0_151, Oracle Corporation
    Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
    Memory: 82107688 bytes (78 MB) / 304087040 bytes (290 MB) up to 2147483648 bytes (2048 MB)
    JVM Flags: 6 total; -XX:+UseG1GC -XX:-UseAdaptiveSizePolicy -XX:-OmitStackTraceInFastThrow -Xmn128m -Xmx2048m -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump
    IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
    FML: MCP 9.32 Powered by Forge 12.18.3.2511 4 mods loaded, 4 mods active
    States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
    UC    mcp{9.19} [Minecraft Coder Pack] (minecraft.jar) 
    UC    FML{8.0.99.99} [Forge Mod Loader] (forge-1.10.2-12.18.3.2511.jar) 
    UC    Forge{12.18.3.2511} [Minecraft Forge] (forge-1.10.2-12.18.3.2511.jar) 
    UE    rabbitz{1.0.0} [Rabbitz] (rabbitz.jar) 
    Loaded coremods (and transformers): 
    GL info: ' Vendor: 'NVIDIA Corporation' Version: '4.5.0 NVIDIA 359.46' Renderer: 'GeForce GT 720M/PCIe/SSE2'
[08:15:49] [Client thread/INFO] [STDOUT]: [net.minecraft.init.Bootstrap:func_179870_a:560]: #@!@# Game crashed! Crash report saved to: #@!@# C:\Users\若冰\Desktop\MC-op\纯净版客户端\.minecraft\crash-reports\crash-2018-01-04_08.15.48-client.txt
