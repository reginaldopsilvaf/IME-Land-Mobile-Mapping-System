.. _introduction:

Introduction
************

About this project
===========================

Development of a system
low-cost portable terrestrial mobile mapping based on a system
dual converging cameras.

In practice, each pair of images taken by the system was used for the
formation of a virtual image. Subsequently, the virtual images were used in the process of
phototriangulation of images to generate a digital surface model (MDS) of a given
region.

The following briefly covers the mounting of a dual system of converging cameras.

#. Setting the cameras in a convergent configuration; 
#. Calibration of cameras to obtain interior orientation parameters;
#. Estimation of camera system assembly parameters;
#. Generation of a virtual image (mosaic of images) for each pair of images taken at the same time by the dual camera system; 
#. Estimation of exterior orientation parameters from at least 3 virtual images using phototriangulation by beams of perspective light rays (Equation of collinearity);
#. Collection of homologous points between virtual images and calculation of their respective XYZ coordinates in the terrestrial reference system via phototriangulation or photogrammetric intersection;
#. Generation of the digital surface model of the region in question from the XYZ coordinates (CloudCompare software);

Description
----------------

This project was proposed as a requirement for completing the digital photogrammetry discipline of the Cartographic Engineering course at the Instituto Militar de Engenharia, taught by professor Daniel Rodrigues dos Santos.  

This project was carried out by 4th year students Matheus Alves Silva and Reginaldo Pereira da Silva Filho during the first semester of 2023. 
