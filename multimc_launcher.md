# Using OpenJDK with MultiMC

This was written for JDK 11 (LTS). The choice was made because JDK 11 (LTS) is the newest long-term support version that worked for me.  You are welcome to try any version you want to, the instructions are the same.

---

1. Select the instance you wish to update
2. Select "Edit Instance" on the right of MultiMC
   - Alternative: Right-click and select "Edit Instance"
   - ![multimc01.png](/images/multimc01.png)

---

1. Select "Settings" on the left
2. Check "Java installation" and enter the location of AdoptOpenJDK 11
   - Default path is `C:\Program Files\AdoptOpenJDK\jdk-11.0.9.11-hotspot\bin\javaw.exe`
3. Check "Java arguments" and adjust extra arguments to taste
   - [Darkosto's recommended arguments](https://pastebin.com/hWWUGGHQ)
     - `-XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M`
   - JDK Versions 14+ use **only** these arguments instead:
     - `-XX:+UnlockExperimentalVMOptions -XX:+UseZGC"`
4. Check "Memory" and adjust as desired for your system.
   - To use Darkosto's setting: Set Min and Max to `8192 MB` (8 gigs)
   - ![multimc02.png](/images/multimc02.png)

---

### That's it. Smile.

### [Back to the main document](README.md)

---

###### *Written by: [Preocts](https://github.com/Preocts) - 2020.10.27*