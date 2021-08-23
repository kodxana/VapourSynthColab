# VapourSynthColab (Updated 23.08.2021) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kodxana/VapourSynthColab/blob/main/VapourSynthColab(2021).ipynb)

A Google Colab notebook set up for both conventional and machine learning-based video processing. Run ESRGAN or MXNet models, OpenCL and CUDA filters, and CPU filters on video frames simultaneously in VapourSynth scripts, or use VapourSynth filters to pre/post process videos for other ML Colab projects, and do it all in the cloud for free. 

![Colab1.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab1.PNG)
![Colab2.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab2.PNG)

Basic usage:
* Log in to Google, open the notebook: https://colab.research.google.com/github/kodxana/VapourSynthColab/blob/main/VapourSynthColab(2021).ipynb
* Run the "Check GPU" and "Run This at Startup" cells.
* Run the cell with the example VapourSynth script, or load your own video and edit it.
* Process the whole video in a scratch cell. 

For basics on VapourSynth and super resolution filters, see the wiki (and links to other guides) here:
* http://www.vapoursynth.com/doc/
* https://github.com/AlphaAtlas/VapourSynth-Super-Resolution-Helper/wiki/VapourSynth-Basics

Browse through VS plugins and scripts here, search for "vapoursynth" on github, or look through the "VapourSynthImports" folder and VapourSynth's imported plugins:
* http://vsdb.top/

I highly recommend stabilizing ESRGAN output with a temporal filter, or using a dedicated video model from another repo. Also, keep in mind that Colab's CPU is very slow, and that sessions are limited to 12 hours, so use GPU accelerated filters wherever possible in scripts with heavy CPU filters, and write your processesed videos to Google Drive or Nextcloud.

For help, just post an issue, or ask in the Animation Upscale Discords.
https://discord.gg/wnCpXpz
