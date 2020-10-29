# Using OpenJDK with the Default Launcher

This was written for JDK 11 (LTS). The choice was made because JDK 11 (LTS) is the newest long-term support version that worked for me.  You are welcome to try any version you want to, the instructions are the same.

---

- Open the Minecraft Launcher
- Select "Minecraft: Java Edition" from the left column
- Select the "Installations" tab at the top
- Click the ". . ." for installation you wish to update and select "Edit"
  - ![default01.png](/images/default01.png)

1. Select "More Options" to display advanced settings
2. Enter the location of AdoptOpenJDK 11
   - Default path is `C:\Program Files\AdoptOpenJDK\jdk-11.0.9.11-hotspot\bin\javaw.exe`
3. Adjust Extra Java Arguments to taste
   - [Darkosto's recommended arguments](https://pastebin.com/hWWUGGHQ)
     - ```-Xmx8g -Xms8g -XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M```
   - JDK Versions 14+ use **only** these arguments instead:
     - `-Xmx8g -Xms8g -XX:+UnlockExperimentalVMOptions -XX:+UseZGC`
4. Click "Save"
   - ![default02.png](/images/default02.png)

---

### That's it. Smile.

### [Back to the main document](README.md)

---

###### *Written by: [Preocts](https://github.com/Preocts) - 2020.10.27*