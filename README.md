# Cloud_Based_Deep_Learning_Platform_for_the_Assessment_and_Management_of_Carotid_Atherosclerosis_GP
---
### Table of Contents:-

- [Features](#Features)
- [Demos](#Demos)
- [Tools](#Tools)
---

## Features

-The project aims to implement a prototype for an integrated system that exchanges information between PACS "Patient List Management", DICOM Viewer, Emulator (DICOM Server) which acts as a modality (MRI, CT, and x-ray), and PACS function to store images With AI feature that helps in the detection and assessment of carotid artery atherosclerosis.

-The existing features used include the following:
1- Basic features: These features include the Angle feature, which measures angles between 2 objects, the Length feature in millimeters, and the Pan feature. There is also the EllipticalROI feature to draw an elliptical shape and calculate its area, mean, and standard division. The FreehandROI feature allows drawing any shape and calculating its area, mean, and standard division. The app has more features, such as the Annotation feature to add notes, the Bidirectional feature to measure length and width simultaneously, and the level feature that enables changing window level, extracting some DICOM tags from the DICOM image, such as transfer syntax, sop class, window center, and window width, is possible through the Details feature, Zoom, Magnify, Rotate, and Probe to get mean and std for a point. Finally, the Marker feature labels point from 1 to 10. Fig.5 shows a display of these features.

2- 3D Rendering: This module renders patient's data in 3 dimensions with ImageCroppingWidget using VTK (The Visualization Toolkit), which is open-source software for manipulating and displaying scientific data.

3- AI (Deep Learning Technique):  Its mission is to draw an automated contour which means localization of the artery in this slice and predict the abnormality of the artery in addition to some of the characteristics like the ratio of narrowing in the artery wall by sending the request for the model that was deployed in the backend to send the contour and display it on the viewer.


---

### Demos
---
1- High Pass Filter in both spatial and frequency domains with histogram equalization


![](https://github.com/Sandra-Essa/Image_Filtering/blob/main/Images/High_Filter.png)

---
2-Low Pass Filter in both spatial and frequency domains with histogram equalization


![](https://github.com/Sandra-Essa/Image_Filtering/blob/main/Images/Low_Filter.png)

---
3- Median Filter in spatial domain with histogram equalization

![](https://github.com/Sandra-Essa/Image_Filtering/blob/main/Images/Median%20Filter.png)

---
4- Laplacian Filter in spatial domain with histogram equalization

![](https://github.com/Sandra-Essa/Image_Filtering/blob/main/Images/Laplacian%20Filter.png)

---
5- Plot RGB image - using Combo Box


![](https://github.com/Sandra-Essa/Image_Filtering/blob/main/Images/RGB.png)

---
### Tools
----
- React.js
- Django
- REST API
- PostgreSQL
- AWS Cloud
- Deep Learning Neural Network.
----
