# UterUS

This repository contains the UterUS dataset - an annotated volumetric dataset of uteri in ultrasound data. 

It consists of three directories - "annotated volumes" (with 141 ultrasound volumes), "volumes without annotations" (with 113 ultrasound volumes) and "annotations" (141 segmentation volumes). All volumes are in compressed nifti2 format (.nii.gz). 
Alongside these, there is a .csv file "volume info.csv" consisting of information about the data, namely the (anonimised) number of the medical center and operator that obtained the ultrasound, the model of the US machine and the group in which the volume/patient belongs to (G - general population (no known problems), M - consecutive misscarriages, I - unexplained infertility and RIF - ). 

