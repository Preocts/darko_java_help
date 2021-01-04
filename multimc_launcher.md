# Using OpenJDK with MultiMC

This was written for JDK 14.

---

1. Select the instance you wish to update
2. Select "Edit Instance" on the right of MultiMC
   - Alternative: Right-click and select "Edit Instance"
   - ![multimc01.png](/images/multimc01.png)

---

1. Select "Settings" on the left
2. Check "Java installation" and enter the location of AdoptOpenJDK 11
   - Default path is `C:\Program Files\AdoptOpenJDK\jdk-14.0.4.12-hotspot\bin\javaw.exe`
3. Check "Java arguments" and adjust extra arguments to taste
   - JDK Versions 14+ use these custom arguments:
     - ```
       -XX:+UnlockExperimentalVMOptions -XX:+UseZGC
       ```
4. Check "Memory" and adjust as desired for your system.
   - To use Darkosto's setting: Set Min and Max to `8192 MB` (8 gigs)
   - ![multimc02.png](/images/multimc02.png)

---

### That's it. Smile.

### [Back to the main document](README.md)

---

###### *Written by: [Preocts](https://github.com/Preocts) - 2021.01.04*