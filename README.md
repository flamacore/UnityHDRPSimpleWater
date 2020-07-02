# Unity HDRP Free Realistic Water
Simple water shader prepared with ShaderGraph in Unity 2019.3.1f1. Has still a lot more work to be done but still might be of use to someone so here it is :) Not likely to get updated frequently but will be updated eventually.

Demonstration Video: https://youtu.be/rvMm2hA8FtM  
Demonstration Video for 2019.3.0f1: https://youtu.be/trioIIom-Qw  
My asset store page with other cool HDRP stuff like glasses, flame vfx and more: https://assetstore.unity.com/publishers/19358

### Update 5
A conributor just fixed a weird ripple issue that happened with camera movement. Merged the pull request.
Credit: https://github.com/ryantwarner

## Update 4 (Long time no see)
Renewed the shader to be compatible for 2019.3.1f1. Added a tiny tiny readme which also includes a link to my asset store page. (Because why not? :) )  
Also added a .unitypackage file for convenience.

### Update 3
Added a working scene file with an example

### Update 2
Added wave controls and Edge foam settings.

### Update
Added waving and a crude way of edge foam. Will improve but still should be useful enough :)

# How to
Just drag 1 or 2 normal maps to the textures and have fun with the settings :)

Settings(Skipping obvious ones like the main color):

Top Color: The outside color of the fresnel effect.

Speed: Sets the speed of blending. Can get jiggy on high speeds.

AngleDim: Sets the power of the fresnel effect (The color changes depending on your angle of view)

Smooth: Specular smooth.

A lot of wave settings (Just tinker with them and you'll see)


Edge Alpha: Adds the alpha from this texture to the foam. Can be used to add some form of simple variance

Clamp Edge Brightness: You will need to adjust this especially if you have bloom enabled.

Edge Offset: How long is the foam?

# To-do

-Preventing "intersection repeats". You'll notice probably after tweaking it some time.

[![water.png](https://i.postimg.cc/kX1tZCkK/water.png)](https://postimg.cc/GHD28W3m)

