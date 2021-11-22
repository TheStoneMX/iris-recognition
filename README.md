# iris-recognition
Iris recognition systems are being used in access control applications. Several airports are using biometric systems including iris recognition steps for granting access to frequent fliers and decreasing the waiting time at security checkpoints.

Currently, iris recognition systems work well with frontal iris images from cooperative users. However, iris recognition has its limitations. It requires NIR illumination when acquiring the NIR iris image. In the visible wavelength, iris pattern from darkly color irises are hard to identify under visible wavelength illumination.

This is due to the high absorption of visible light by darkly colored irises, so that little of the identifying structure of the iris can be imaged and extracted.
Moreover, many factors affect the quality of an eye image, including: defocus, motion blur, occlusion, glare, resolution, image contrast, and deformation.are some examples of poor quality eye images. 

How to perform eye image quality measurement including iris is a challenging task. that is what is proposed on this repository as a base line,a feature quality-based unconstrained eye recognition.

Different from periocalur recognition which extracts features from facial region in the immediate vicinity of the eye,our eye recognition uses the information from iris and sclera areas. First, the iris area and sclera areas will besegmented by this segmentation approach. Iris and sclera features will be extracted

![Architecture](https://github.com/TheStoneMX/iris-recognition/blob/main/images/eye-recognition%20system.png)

Iris recognition processing generally consists of the following steps: 
  1.- Image acquisition
  2.- Iris segmentation 
  3.- Normalization 
  4.- Feature extraction and 
  5.- Classification
  
  
