Hello Guys! This is a repo with my changes on Adreno 615.93 Drivers i changed vulkan to 676.66 because the one from 615.9X X={0,1,2,3} was broken.
I have been running this for a while on my own phone which is A660 OnePlus 9 Pro and has been tested as well on various other devices like OnePlus 11R and Oneplus 7 and seem pretty stable.
Q:Why this combo and not go fully for OGL and VK 676.66 but do this instead?
A:v615.93 maintains some sanity of heat and is not as power hungry as 676.66 on A6XX GPUs.
You can include this on your ROM builds just be careful as some ROMs like Pixelage,Crdroid,LineageOS doesn't boot due to libgpu_tonemapper.so files so just dont use them if the drivers don't boot on your first try.
Cheers!
