# Using OpenJDK with MultiMC

1. Select the instance you wish to update
2. Select "Edit Instance" on the right
   - Alternative: Right-click and select "Edit Instance"
   - ![multimc01.png](/images/multimc01.png)

---

1. Select "Settings" on the left
2. Check "Java installation" and enter the location of AdoptOpenJDK 11
   - Default path is `C:\Program Files\AdoptOpenJDK\jdk-11.0.9.11-hotspot\bin\javaw.exe`
3. Check "Java arguments" and adjust extra arguments to taste
   - [Click here for Darkosto's recommended arguments](https://pastebin.com/hWWUGGHQ)
   - **Note** If you use these arguments, remove `-Xmx8g -Xms8g` from the line (see step 4)
4. Check "Memory" and adjust as desired.
   - From step three: Set Min and Max to `8192 MB` (8 gigs)
   - ![multimc02.png](/images/multimc02.png)

---

### That's it. Smile.

### [Back to the main document](README.md)

---

###### *Written by: [Preocts](https://github.com/Preocts) - 2020.10.27*