
# Facial Landmark Detection

This project aims to demonstrate that synthetic data may be used to train facial analysis algorithms before applying them in real-world circumstances, and that it is possible to perform face-related computer vision in the wild using just synthetic data. 

Facial landmark points detection was done using: \
•	Face detection using MTCNN\
•	Landmark detection using - ResNet18, ResNet50 and Xceptionet.


## Demo

For each notebook, the training dataset should be downloaded from the given link: \
https://github.com/microsoft/FaceSynthetics

For testing, the corresponding trained model should be uploaded as 'face_landmarks.pth' to the working directory of the notebook. \

4 of the videos have been included in the repository for testing. The rest can be downloaded from here: \
https://ibug.doc.ic.ac.uk/resources/300-VW/.  


## Authors

- [@Janani Nataraj](jna102@sfu.ca)
- [@Parth Gulati](pga56@sfu.ca)


## References
1.	Wood, E., Baltrusaitis, T., Hewitt, C., Dziadzio, S., Johnson, M., Esterllers, V., Cashman, T., Shotton, J., Fake It Till You Make it, Microsoft - https://microsoft.github.io/FaceSynthetics/
2.	Synthetic and Real-World Data in Facial Landmark Detection Models, Datagen,https://datagen.tech/blog/facial-landmark-detection-blog-one/
3.	Sagonas, C., Antonakos, E., Tzimiropoulos, G., Zafeirious, S., Pantic, M., 300 Faces In-The-Wild Challenge: database and results, chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://ibug.doc.ic.ac.uk/media/uploads/documents/sagonas_2016_imavis.pdf
4.	Rosebrock, A.,  Facial landmarks with dlib, OpenCV, and Python, https://pyimagesearch.com/2017/04/03/facial-landmarks-dlib-opencv-python/
5.	J.Shen, S.Zafeiriou, G. S. Chrysos, J.Kossaifi, G.Tzimiropoulos, and M. Pantic. The first facial landmark tracking in-the-wild challenge: Benchmark and results. In IEEE International Conference on Computer Vision Workshops (ICCVW), 2015. IEEE, 2015.


