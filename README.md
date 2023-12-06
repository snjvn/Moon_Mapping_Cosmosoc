ISRO Moon Mapping Project
Cosmosoc, The Space Data Science Club, IIT Dharwad

Problem:
**Development of an AI/ML model to generate high (~30 cm) resolution
lunar terrain image from medium/low (5 m / 10 m) resolution terrain image.**
The following 2 payloads are used for the project  
For low resolution images- TMC-2
For High Resolution Images- OHRC

Dataset: 
TMC-2 - https://pradan.issdc.gov.in/ch2/protected/browse.xhtml?id=tmc2  
OHRC - https://pradan.issdc.gov.in/ch2/protected/browse.xhtml?id=ohrc

Files: This section contains a brief discription of the files used in the project:
[1] Check_for_Intersection.ipynb- This file contains a basic code for checking the overlapping intersections between TMC-2 and OHRC images and classifying them in separate folders namely ohrc and tmc_crop. Ohrc folder contains the images in ohrc that have a overlap with some image in TMC-2. tmc_crop contains the cropped TMC-2 images i.e that they are the low resolution overlapping region



### Reference
* [1] [Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://arxiv.org/abs/1609.04802)
* [2] [Is the deconvolution layer the same as a convolutional layer ?](https://arxiv.org/abs/1609.07009)




### License

- For academic and non-commercial use only.
- For commercial use, please contact tensorlayer@gmail.com.
