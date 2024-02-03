# Vision Field Mapper VR

This repo contains the UE5 source code, allowing anyone to download the actual UE5 project and extend/modify it as needed. If you just want to run the program as-is, [you can download the Windows 64-bit version here](https://drive.google.com/file/d/1_Nuu3CnVLewO5Te0tNj5nsaQiO-xWzNF/view?usp=sharing). If you would like me to build the source code for another platform on my end, feel free to create an issue and specify which platform and why (though it may be quicker to download and rebuild the source code directly, as I cannot promise I will have bandwidth to do this in a timely manner).

Vision Field Mapper is a simple approach to generating a mapping of someone's effective field of vision using VR. The VR headset shows the user 'questions' that will identify possible problems by location, color, shape, size or contrast. 
The 'Tester' administrates this test, by observing the prompts on the monitor of the same computer (video is streamed both to the VR headset, as well as the main monitor of the computer).
I have not tested the migration of source code to other systems, and cannot guarantee there won't be issues. I attempted to comment my code (Visual Blueprinting) as clear as possible, but I cannot promise to be available to explain any design choice that was made during the development of this tool.

When the test is complete, the program will generate 3 images (2 for the 2 tests to show success based on location/size, and 1 for a summary of shape/color success for all tests). I have added some example maps to demonstrate how they look to the repo (as well as further below in this README). **NOTE: All files related to what I have personally added/modified, all exist under the folder 'Content/VisualFieldTest'.**

# Example Maps

![](https://github.com/jwmcfar2/VisionFieldMapper/blob/main/ExampleMaps/ResultMap_ColorShape_2024FEB03_0609.png)

![](https://github.com/jwmcfar2/VisionFieldMapper/blob/main/ExampleMaps/ResultMap_2024FEB03_0609.png)

![](https://github.com/jwmcfar2/VisionFieldMapper/blob/main/ExampleMaps/ResultMap_Inv_2024FEB03_0609.png)
