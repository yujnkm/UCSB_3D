# UCSB_3D
<img
  src="ucsb_logo.png?raw=true"
  alt="Screenshot of Unity 2018 showing the inspector with Readme content."
  width="880"
  height="70"
/>


The project includes 3D models of three locations at the University of California, Santa Barbara. Each physical environment was scanned using LiDAR and post-processed to run in Unity game engine software. 

1) Kirby Crossing [Google Map (34.41471, -119.84060)](https://www.google.com/maps/place/34%C2%B024'53.0%22N+119%C2%B050'26.2%22W)

2) Student Affairs [Google Map (34.41630,-119.84730)](https://www.google.com/maps/place/34%C2%B024'58.7%22N+119%C2%B050'50.3%22W)

3) Life Science [Google Map (34.41207,-119.84425)](https://www.google.com/maps/place/34%C2%B024'43.5%22N+119%C2%B050'37.9%22W)

All 3D models are optimized as Unity environments and run well on any target device.



# Getting Started
Follow these instructions to install necessary software. These instructions have been tested on the following versions:

* Unity 2020.3.20f1 LTS
* Windows 10 SDK 18632
* Visual Studio Community 2019 ver. 16.11.4
* Once installed, clone this repo and open the project in Unity or Unity Hub.
* Item 1

The main scene can be found under Assets > PersonalAR > Scenes.







All 3D models are optimized as Unity environments and run well on any target device.


<img
  src="readme-screenshot.png?raw=true"
  alt="Screenshot of Unity 2018 showing the inspector with Readme content."
  width="439"
  height="336"
/>

## 1. Kirby Crossing

Kirby Crossing
34°24'53.0"N 119°50'26.2"W 
Google Map (34.41471, -119.84060)
https://www.google.com/maps/place/34%C2%B024'53.0%22N+119%C2%B050'26.2%22W

Download this [project’s Unity package](build/Readme.unitypackage?raw=true).

In your own Unity project, add the Readme by choosing “Assets” → “Import
Package” → “Custom Package” from the Unity editor’s menus.

<img
  src="readme-import-screenshot.png?raw=true"
  alt="Screenshot of Unity 2018 showing how to import a custom package."
  width="448"
  height="244"
/>

## 2. Student Affairs
Student Affairs/ Administrative Services
34°24'58.7"N 119°50'50.3"W
Google Map (34.41630,-119.84730)
https://www.google.com/maps/place/34%C2%B024'58.7%22N+119%C2%B050'50.3%22W

First make sure the Readme is shown in the Unity editor “Inspector” tab. Then
the file can be edited by clicking on the drop-down menu to the right of the
“Inspector” tab and picking the “Debug” option.

The Readme contents are divided into “Sections”. Each section has a “Heading”
and a “Text” body.

Each section can have an optional “Link Text” and “Url” field. Adding both of
these fields will allow a user to open your link in their web browser.

To add more sections to the Readme, change the “Size” field at the top of
“Sections”.

The current icon used in this inspector is found at:
    »Readme / Icons / Readme_Builder.png

You can use any PNG file (and file name) for the icon.

1. Add the new icon to the project.
2. In the Unity inspector, change the icon’s “Texture Type” to “Editor GUI and
   Legacy GUI”.
3. Then open the “debug” version of the Readme inspector and drag the new icon
   into the “Icon” field.

## 3. Life Science

Life Science/ Nobel Hall
34°24'43.5"N 119°50'37.9"W
Google Map (34.41207,-119.84425)
https://www.google.com/maps/place/34%C2%B024'43.5%22N+119%C2%B050'37.9%22W

Adding long text to the “text” field in Unity’s “debug” screen is cumbersome.

The Readme file can also be edited by opening this project’s “Readme.asset” file
in a text editor. The file is in Yaml syntax and can contain UTF-8 characters.

For example, this section was written using a text editor and uses the Yaml “|-”
(pipe and dash) characters to add multi-line text to a single yaml value.

[Learn about Yaml syntax](http://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html).

## Exporting Packages
All three models can be found under (UCSB_3D > Assets > Scenes) the Scenes folder. Each Unity scene contains each model. You can proceed to gererate standalone Unity package by  right clicking the scene from the Unity editor’s menus and select ***Export Package...***

<img
  src="4_1.png?raw=true"
  alt="How to cite our work."
  width="880"
  height="450"
/>



## License & Citation
This repository contains models we constructed with a lot of care and effort. If you use the 3D model in your research, please cite us using ***Cite this repository*** found in the repository landing page.

<img
  src="5_1.png?raw=true"
  alt="How to cite our work."
  width="880"
  height="400"
/>


Read the [license](LICENSE.md).
