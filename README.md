# ShutTheCamUp

Removes the camera shutter and high-pitched beep sound from the Nintendo 3DS (works on all 3ds apps)

[Installation](#installation)

[Why?](#why-tho)

[Does it work on both Old and New3DS?](#does-it-work-on-both-old-and-new-3ds)

[How is it possible?](#how-is-it-possible)

![image](https://github.com/TehFridge/ShutTheCamUp/assets/85436576/e2c71d2a-f0c6-4166-b4f5-c48f268e05a0)

# DISCLAIMER
I do not condone any misuses of this patch for malicious purposes or whatever.


# Why tho?
Imagine you are playing your 3ds in a cafe or smt, you need to use the camera feature in some game (for example. Face Raiders) and suddenly the shutter sound bursts out of the speakers and people look at you weirdly, we wouldnt want that. 

Also like... phones don't do that sort of thing (well maybe in japan, china cause there the law demands that anything with a camera has to have a shutter sound)

I mostly created this patch cause i like the vibe of vlogging with a 3ds. It has its charm you know.

# How is it possible?!
The shutter sound was embedded in some system process, we just discovered it now lol. So i just decided to null the bytes with audio data, and it worked!


# Does it work on both Old and New 3DS?
Yup. there are two seperate patches individually for the new and old model of the console.


# Installation

**Make sure you enable game patching and loading external FIRMS and modules first!**

for dummies: hold select while powering on the console to access the luma menu

![image](https://github.com/TehFridge/ShutTheCamUp/assets/85436576/a8e2fcef-e7a6-40b1-afcc-ba5b00d349c4)



## For users that are below Luma3DS v13:

**Put the .ips file like this:**

Both Old and New3DS: /luma/titles/0004013000001602/code.ips

## For users that are on Luma3DS v13 or higher:

**Put the .ips file like this:**

Both Old and New3DS: /luma/sysmodules/0004013000001602.ips

