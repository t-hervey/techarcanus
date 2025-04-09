+++
title = "Formbot 350mm Voron 2.4 Build"
path = "projects/voronbuild"
[taxonomies]
tags = ["3dprinting", "voron", "project"]
+++
# A bit of background
I got my start in 3d printing in November of 2022 when my wife sneakily hid an Ender 3 S1 right under my nose for weeks and then gave it to me for our anniversary.  Just about as soon as I had it printing reliably, I started tinkering with it.  Camera mounts, alternative part cooling, installing klipper, and more.  This made me realize that what I really enjoyed most was tinkering with my printer and occasionally using it to actually produce something useful 😃.

It wasn't long before I got the itch to build my own printer.  A Voron felt like too big of project to start with so after a bit of research and poking around the internet I discovered [Rolohaun 3D's Rook](https://www.rolohaun3d.ca/3d-printers) printer that was touted as being a good first printer to build for beginners. I self sourced all of my components and by December 2023 I had my very own Rook 2020 MK1

{{ feature_image(path="/content/pages/projects/voron_build/Rook2020MK1.jpg", width=0, height=500, op="fit_height", caption="This was the photo I used to get my Rook serial, #165") }}

Building the Rook was definitely fun and the [community](https://discord.com/invite/rolohaun-3d-946191040682008666) was great to work with but it only increased my desire to eventually build the voron.

So that brings us to the present, near the end of 2024 I ordered a 350mm Formbot Voron 2.4 R2 and once the holidays had passed I have finally unboxed it and started building.

# Unboxing and Building the Frame
So many parts had ended up covering the entire table and then some.

{{ feature_image(path="/content/pages/projects/voron_build/VoronUnboxed.jpg", width=0, height=500, op="fit_height", caption="") }}

Getting the frame together was pretty straightforward.

{{ feature_image(path="/content/pages/projects/voron_build/VoronFrameBuilt.jpg", width=0, height=500, op="fit_height", caption="") }}

# Baseplate and starting assembly of Z-Drives
So I've had a few delays.  I found that I had overlooked printing one part of the z motor mount and needed to print those.  Unfortunately my Ender 3 S1 that I had printed all my parts on had recently suffered a catastrophic blob of death and resulted in needing to replace the heat block.  Which meant ordering parts (I really should keep a few of those handy as it seems to happen about once a year...)  Finally got the ender rebuilt and tuned back up.  Turns out the likely reason that I got blob of death in the first place was that my print head had started to wobble some and the eccentric nut on the carriage needing tightening up.

So parts printed and ready start building again.  Got the first of the z motor mounts done.  Couple of things I learned:

- Getting the 625 bearings on the shaft and in the right position can be a real pain.  I ended up having to use a nail tap to get them into the right position.  I've since read that either sticking the shafts in the freezer overnight or doing the light sanding on them can help with getting them on and in the right position.
- Definitely recommend having the pulley jig for spacing, made getting the pulley on the motor so much easier: [Voron 2.4 Pulley Jig](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/Tools/pulley_jig.stl)

{{ feature_image(path="/content/pages/projects/voron_build/ZDriveMountPulley.jpg", width=0, height=500, op="fit_height", caption="Adjusting the 625 bearings when they didnt line up with the mount was a pain!") }}

{{ feature_image(path="/content/pages/projects/voron_build/ZDriveMountAssembled.jpg", width=0, height=500, op="fit_height", caption="First of four") }}

And finally getting it attached to the frame with the motor as well.  Definitely like how sharp the classic Voron black and red color combo looks.

{{ feature_image(path="/content/pages/projects/voron_build/ZDriveInstalled.jpg", width=0, height=500, op="fit_height", caption="") }}

# Assembly of Z-Drives 2, 3, & 4
## Z-Drive #2
Well, made my first mistake. I had misread these directions from the assembly manual:

{{ feature_image(path="/content/pages/projects/voron_build/ZBeltAssemblyManual.png", width=0, height=500, op="fit_height", caption="I had taken this to mean it should be positioned at the end of the shaft 🤦‍♂️") }}

What I didn't miss in the directions was the note that said to be sure to use thread locker to make sure on all screws which I dutifully did.

This in turn meant I couldnt get this screw back out of the pulley and ended up striping the screw trying to do so.  My kit only has the exact number of pulleys of this size that are needed.  But by the end of tomorrow, I'll have a whole supply of 20T 9mm pulleys curtesy of Amazon.  Live and learn.

{{ feature_image(path="/content/pages/projects/voron_build/StuckScrewPulley.jpg", width=0, height=500, op="fit_height", caption="RIP little pulley, hopefully you are the only ruined part of this build. 🤞 At least you were cheap to replace.") }}

I did figure out a neat trick for aligning the motor mounts on the 2020 extrusion.  If you place one of the allen wrenches through the holes you can usse them to help align the t-nuts into the right position making it much easier to get everything aligned before inserting the screws.

{{ feature_image(path="/content/pages/projects/voron_build/2020TNutAlignment.png", width=0, height=500, op="fit_height", caption="") }}