# CMPM-121-KZSC-LiDar-Unity
Creating a simple scene in Unity

|  |  |  |  | PROJECT CAN BE FOUND WITHIN THE "MASTER" BRANCH! |  |  |  |  |

CMPM 121 Project 1:
Kai Turner
“KZSC 3D LiDar Scene”

  For this project I decided to take advantage of LiDar technology now available at the consumer level in portable devices. LiDar uses infrared light to get parallax information from real world objects. Using free software and a newer LiDar enabled iPad, you are now able to create Live Scale 3D scans of anything from small objects to large rooms.

  I began by borrowing my roommates iPad pro to create room scans of KZSC, UCSC’s FM radio station, who I happen to work at. KZSC is an incredibly visually interesting space, perfect for this project. I thought that creating a 3D version of the station would be not only interesting but practical for other purposes, such as sharing where I work to family who haven’t been there. I spent the first two weeks scanning, and scanning again, to get a collection of relatively high quality Scans of the rooms going. By the time I brought the scans into Unity, I had 3 rooms, a hallway, and the entire lobby scanned, roughly 65% of the station.

  My final objects currently consist of 7 total scans, 3 “planes” that patch some of the holes, and 5 “critters” pulled from the Unity Asset Store. The skybox is a Google street view image of the Merril parking lot just below the station, as close as I can get to the station short of creating my own 360 pictures.

  My main character(s) are the “Crossy Road” voxel animals that have taken residence within the building. They all have their own orbit cameras that can be controlled with a mouse, designed to allow a tour of the different rooms. Hold left click while moving the mouse to orbit, scroll to zoom in and out.

Assets:

LiDar scans: Created with the “PolyCam” app: https://poly.cam/
Voxel Animals pulled from https://assetstore.unity.com/packages/3d/characters/animals/5-animated-voxel-animals-145754
Skybox pulled from Google Maps Street View
Patch material assets created by me taking pictures of the carpet and ceiling of KZSC, and then matching them within the scene.
Camera Orbiting script (Thanks!): https://gist.github.com/3dln/c16d000b174f7ccf6df9a1cb0cef7f80
