# jm_almostPhysicalSunAndSky
# Generates an adjustable and animatable sun and sky background plate. Inspired by the physical sky implementation in 3D renders like Arnold



The gizmo outputs a sun and sky background plate or each element isolated. It can also output a spherical 3D scene or a 3D light

There are built in controls for sun and sky control, simple color correcting and perspective adjustments for quick and easy use.

There are optional inputs for an external camera and an external sun (or moon).


Gizmos/jm_almostPhysicalSunAndSky_v003/jm_almostPhysicalSunAndSky_v002.gif




It is unfortunately not an implementation of the Hosek-Wilkie sky radiance model as it is beyond skills to implement that, but it is made to look like the physical sky implementation in Arnold using ACES. 

 

INSTALLATION:

The gizmo requires some footage (included in the .zip). It can either be pointed to directly in the gizmo UI, or the flowing lines can be added to init.py (remember to replace ......your.path....... with the correct path)

gizmoSupport = '/......your.path......./Gizmos/gizmoSupport'
nuke.pluginAddPath(gizmoSupport)

 

Tested back to Nuke 12.2 on windows.

Updated to support Nuke 12 and earlier 3D system nodes
