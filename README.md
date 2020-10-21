**Anomaly detection in images of Industrial parts using GANs** \
The repo contains 2 images one of Good and another of Bad industrial part on basis of which we have to build a model to classify any part into Good or Bad classes. \
The approach is to augment the Good Image with various affine techniques and then train a GAN to generate a similar representation of the image, this will amplify the differentiating features in the image.upon inference a similar representation of the query image is generated and then compared with our representations of the good image.The anopmaly score is calculated on the basis of perceptual loss between the two representations. \
**Sample Representation:** \
QueryImage- \
![Query Image](https://github.com/Vaibhav21pandit/Anomaly_Detection_GAN/blob/main/query.png) 

Difference Heatmap- \
![Anomaly Image](https://github.com/Vaibhav21pandit/Anomaly_Detection_GAN/blob/main/anomaly.png)
