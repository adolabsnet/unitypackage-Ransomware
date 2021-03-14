# .unitypackage Ransomware


<p align="center">
  <img width="300" height="300" src="https://cdn.discordapp.com/attachments/804862672675799080/820642819830972467/tumblr_inline_pexz54of541un6iqp_540.gif">
</p>

This is a proof of concept to encrypt files using a unitypackage.

**This script should not be used to encrypt other systems but should be used for study purposes.**

!!I assume no liability if you encrypt your files during testing!!

Check out my [Discord Server](https://discord.gg/peC5MntJw2)

### Step-by-Step Guide to use the Script

* Download this Script
* Add the script to your future .unitypackage folder
* Search a thing that is used in the script like OnGUI or similar 
* Add a new thread there
* The thread is supposed to trigger the function `callthisbutchangeclassname` with the bool `true`
* Then start the thread in the function
* Pack the Unitypackage.

**This script uses a password for each file, so it is impossible to decrypt them**

For any support send me a e-mail: `admin@astronyia.xyx`

### Todo/next updates
- [x] Simple Ransomware
- [x] Support Random String as Password
- [ ] Random Salt Generator
- [ ] Random File Extensions
- [ ] Download other Ransomware to Encrypt after Unity Close
- [ ] Remove Antivirus and Replace with Unity
- [ ] Test package
- [ ] Admin bypass
- [ ] Store Filepassword to DB over a API
- [ ] Download other Maleware in background
