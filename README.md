# UnityHDRPSimpleWater
Simple water shader prepared with ShaderGraph in Unity 2018.3.6. Has still a lot more work to be done but still might be of use to someone so here it is :) Not likely to get updated frequently but will be updated eventually.

Demonstration Video: https://youtu.be/rvMm2hA8FtM


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

