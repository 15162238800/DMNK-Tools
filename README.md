<img align="left" style="margin-right:40px" src="https://github.com/DominikLingenover/DMNK-Tools/blob/master/resources/DMNK_Logo_Stencil.svg" width="128">

## DMNK Shelf | Workflow oriented Python Scripts / HDAs

![Twitter Follow](https://img.shields.io/twitter/follow/j0zen_?label=Twitter&style=for-the-badge)
<br></br>

## Overview

DMNK Shelf is a set of Python Scripts and HDAs to speed up your workflow.
All tools are designed to be easy to use and take away the manual labour involved with daily tasks an artist may face.
Render related scripts work with all major engines except Mantra. (Arnold, Octane, Redshift, Renderman, VRay)

## Current Toolset

Tool | Functionality
---- | -------------
Asset Checker | Manages missing files in your project & more!
Material Importer | Quickly imports textures and builds whole shading networks.
SpeedTree Importer | One-Click solution to import SpeedTree assets.
RS Samples Editor | A GUI to set up individual samples quicker **(EXPERIMENTAL)**
Intel + Nvidia Denoiser | An HDA to process renders with Intel or Nvidia denoiser in PDG.
ACES Batch Converter | An HDA to batch convert images and textures to ACES in PDG.
ACES Convert | A simple HDA to save a few clicks when converting an image to ACES in COPs.
> All tools have been tested in Houdini 17.5 on Windows 10. Only minimal testing happened on Linux. 

> Note: The Denoiser HDA requires the pre-compiled versions from [Declan Russel](https://github.com/DeclanRussell)

## Installation Guide

1. Download the latest [release](https://github.com/DominikLingenover/DMNK-Tools/releases)
1. Unpack the file to your desired location 
1. Set up your environment with the new [packages](https://www.sidefx.com/docs/houdini/ref/plugins.html) system or the old [houdini.env](https://www.sidefx.com/docs/houdini/ref/env.html) system.
Example files are provided in the main directory. 
[Packages file](https://github.com/DominikLingenover/DMNK-Tools/blob/master/dmnk_tools.json) or 
[houdini.env](https://github.com/DominikLingenover/DMNK-Tools/blob/master/houdini.env)
1. Add the 'DMNK' shelf to your toolbar.
