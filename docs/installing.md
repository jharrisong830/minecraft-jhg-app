---
sidebar_position: 1
---

# Installing required software

The following items need to be installed to connect to the server:

- An installation of Java 21 (OpenJDK builds can be found [here](https://jdk.java.net/archive/))
- [Prism Launcher](https://prismlauncher.org), so that you can easily import an instance without downloading individual mods
  - Any installation method will work


## Java 21 for Windows

You can skip this step if you already have Java 21 installed. You can also install it however you like. This is just how I would install it if starting from scratch:

1. Create a folder in your home directory (i.e. `C:\Users\%USERNAME%\`) named `.jdks`
    - For example, `C:\Users\johng\.jdks`
2. Download the latest Java 21 release for windows as a ZIP file (download [here](https://download.java.net/java/GA/jdk21.0.1/415e3f918a1f4062a0074a2794853d0d/12/GPL/openjdk-21.0.1_windows-x64_bin.zip)), and extract the ZIP file
3. Move the `jdk-21.0.1` folder inside of the `.jdks` folder

Later on, we will specify the binary `.jdks/jdk-21.0.1/bin/javaw.exe` if it is not auto-detected by the launcher.


## Prism Launcher

Prism Launcher allows you to create separate instances of Minecraft, each with different versions, mods, and configuration options. We will import an instance to use for this server

1. Download Prism Launcher from their [website](https://prismlauncher.org/download/windows/).
    - Any install method is fine, so long as you can locate and run the launcher
2. Open Prism Launcher and complete any necessary setup. Log in with your Microsoft Account in order to download Minecraft
3. Import `instance.zip` (`TODO`) by dragging it into the main Prism Launcher window


---

You should now have all of the necessary software to run the instance and connect to the server. You can launch the imported instance and try starting a single-player world to make sure there are no errors.
