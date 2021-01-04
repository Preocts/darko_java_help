# Using OpenJDK with the Default Launcher

This was written for JDK 14.

---

- Open the Minecraft Launcher
- Select "Minecraft: Java Edition" from the left column
- Select the "Installations" tab at the top
- Click the ". . ." for installation you wish to update and select "Edit"
  - ![default01.png](/images/default01.png)

1. Select "More Options" to display advanced settings
2. Enter the location of AdoptOpenJDK 14
   - Default path is `C:\Program Files\AdoptOpenJDK\jdk-14.0.2.12-hotspot\bin\javaw.exe`
3. Adjust Extra Java Arguments to taste
   - JDK Versions 14+ use these arguments:
     - ```
       -Xmx8g -Xms8g -XX:+UnlockExperimentalVMOptions -XX:+UseZGC
       ```
4. Click "Save"
   - ![default02.png](/images/default02.png)

---

### That's it. Smile.

### [Back to the main document](README.md)

---

###### *Written by: [Preocts](https://github.com/Preocts) - 2021.01.04*