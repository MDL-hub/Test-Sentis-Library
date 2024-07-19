Software and Library Versions

Visual Studio Community 2022
Unity editor version 2023.2.20f1
Sentis version 1.5.0-exp.3


Usage

Open the Unity app and import the Sentis library.
Add the c# script to the Main Camera.
Create a Raw Image in the scene and link it as the displayImage
Drag the Model 1000 Epochs.ONNX file into the model asset field
Drag the classes.txt on to the labelAssets field
Put a video file in the Assets/StreamingAssets folder and set the name of videoName to the filename in the script
Set the fields for the bounding box texture sprite and the font

Issue

It can run ONNX files but not the quantized ONNX files.
How to run quantized packages is included in the Sentis Library as a sample.
