# 3D Bounding Box Estimation using Deep Learning and Geometry

## Project Description:
 We propose a techniquefor 3D object estimation from an image andthis technique starts
 by predicting stable 3D object attributes using a deep convolutional neural network,
 in contrast with conventional methods that only concentrate on regressing 3D object
 orientation. These estimates are then combined with geometric constraints derived
 from 2D item bounding boxes to generate accurate 3D bounding boxes. By integrating
 deep learning and geometric concepts, our model effectively addresses the conversion
 problems resulting from 2D bounding boxes, generating accurate and trustworthy 3D
 object estimations.
 For this proposed technique we used a subset of the KITTI dataset that consist of labeled
 images, unlabeled test images and important calibration data, was used to evaluate the
 technique. Visual inspection of projected 3D bounding boxes on test images was used
 to evaluate the model’s performance, with an emphasis on alignment accuracy, object
 location, and orientation stability. The outcomes show that various objects scales, and
 congested locations our method reliably generates reliable and robust 3D bounding
 boxes.
 Further, proposed model evaluation shows how well geometric constraints and acquired
 deep features work together to improve the overall performance of 3D object estima
tions. Despite certain drawbacks, like alignment at extreme orientations and less precise
 results in situations with a lot of chaos, the outcomes confirm the robustness, accuracy,
 and precision of our methodology.
