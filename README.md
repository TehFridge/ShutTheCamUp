# ShutTheCamUp
Removes the shutter and high-pitched beep sound from the Nintendo 3DS Camera App

![image](https://github.com/TehFridge/ShutTheCamUp/assets/85436576/e2c71d2a-f0c6-4166-b4f5-c48f268e05a0)
# How is it possible?!
The shutter sound was embedded in some system process, we just discovered it now lol. So i just decided to null the bytes with audio data, and it worked!

# Does it work on Old and New 3DS?
Yup. there are two seperate patches individually for the new and old model of the console.

# Installation
**The title ID's are:**

0004013020001602 - New 3DS

0004013000001602 - Old 3DS

## For users that are below Luma3DS v13:

**Put the .ips file like this:**

Old3DS: /luma/titles/0004013000001602/code.ips

New3DS: /luma/titles/0004013020001602/code.ips

## For users that are on Luma3DS v13 or higher:

**Put the .ips file like this:**

Old3DS: /luma/sysmodules/0004013000001602.ips

New3DS: /luma/sysmodules/0004013020001602.ips
