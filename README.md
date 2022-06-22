# Threejs-VR-Astronomical-Observatories (updating)
An experiment to recreate VR experience of astronomical observatories around the world.

<img src="images/1.jpg" width="640">

The Canadian Hydrogen Intensity Mapping Experiment (CHIME) radio telescope is located in Penticton, British Columbia, Canada. Each telescope is a 100m x 20m cylindrical reflector. The grey-white columns are 1.8m tall.<br>

# Hardware

Oculus Quest (tested Quest One, update 35.0, Oculus browser 18.0)<br>

(should work on other VR headsets in Chrome 96.0 and Firefox 94.0)<br>

# Installation

No installation. In Oculus Quest, open Oculus Browser and:<br>

[https://physicslibrary.github.io/Threejs-VR-Astronomical-Observatories/examples/threejs_vr_chime.html](https://physicslibrary.github.io/Threejs-VR-Astronomical-Observatories/examples/threejs_vr_chime.html)

(feb 2022, under construction, link disabled)<br>

Should work (no VR) on web browsers (latest Chrome, Firefox, Safari) on smartphones and desktop/laptop computers. Code threejs_vr_chime.html has threejs' orbit controls to allow camera to look around a target (one/two/pinch/slide fingers for mobile devices, and 3-button mouse for others).<br> 

Code is minimal (no error checking or physics simulation). An experiment to jumpstart other experiments.<br>

# A short tutorial on making 3D glTF from DEM geoTIFF. (under construction)<br>

<img src="images/2.jpg" width="640">
<img src="images/3.jpg" width="640">
<img src="images/4.jpg" width="640">
<img src="images/5.jpg" width="640">
<img src="images/6.jpg" width="640">
<img src="images/7.jpg" width="640">
<img src="images/8.jpg" width="640">
<img src="images/9.jpg" width="640">

# Credits

This experiment is inspired from a collaboration with organizers, astrophysicists, educators, writers, programmers at<br>

https://www.stemxr.org/<br>

ESA\_Gaia\_DR2\_AllSky\_Brightness\_Colour\_Cartesian\_2000x1000.png<br>
Date: 25 April 2018<br>
Satellite: Gaia<br>
Copyright: ESA/Gaia/DPAC, CC BY-SA 3.0 IGO<br>
[http://sci.esa.int/gaia/60196-gaia-s-sky-in-colour-equirectangular-projection/](http://sci.esa.int/gaia/60196-gaia-s-sky-in-colour-equirectangular-projection/)<br>

U.S. Geological Survey's Earth Explorer for DEM (Digital Elevation Map) data.<br>

https://earthexplorer.usgs.gov/<br>

A free and open source geographic information system to merge DEM with satellite images to export 3D models (glTF format) for threejs.<br>

https://qgis.org/en/site/<br>

A computer graphics tool to create, import, and export 3D models.<br>

https://www.blender.org/<br>

chime-dec-7-2021.glb<br>
created using Blender<br>
(CC BY 4.0)<br>

chime-dem-dec-7-2021.glb<br>
derived from USGS GeoTIFF n49_w120_1arc_v3.tif, QGIS, and Blender.<br>

# References

[https://threejs.org/](https://threejs.org/)<br>

https://chime-experiment.ca/en<br>

<br>Copyright (c) 2021 Hartwell Fong
