# URP-Outline

This is a Outline URP RenderFeature for Unity versions 2022 and above.
I made this by Ben Golus's fantastic article https://bgolus.medium.com/the-quest-for-very-wide-outlines-ba82ed442cd9.
To fit the URP feature, I edited a little bit to the shader. 

*This Outline works with Layer Mask. To set which object that the outline will be draw at, you need to set them to a specific Layer.*

# How to use

1. Go and copy the files in this path to your Unity Project: URP-Outline/UnityProject/Assets/RenderFeatureOutline/
2. Add this RFO RenderFeature to your renderer.
3. Assign the RFOMaterial.mat to RFO.
4. Setup other settings such as which layer should outline be drawing on.
5. Change your 3D Object's layer to the outline layer. And you will see the Outline!

# When you get confused
Please download the whole project, I have a Sample in my project, maybe this will help.
