

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

 
### Tumor Detection AI 

![2023-05-03 21-14-52](https://user-images.githubusercontent.com/44925899/236008091-43191326-95e3-402a-a041-97b434093af8.gif)


<!-- ABOUT THE PROJECT -->
## About The Project
 
An AI image classification project for classifying tumor and non-tumor brain MRI images. <br />
The data was downloaded from the following kaggle dataset: https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor <br />
Data was stored in a S3 bucket. <br />
The classifier and endpoint configuration were created using the SageMaker AWS service and documented in the notebook file. <br />
The backend sends requests to an Amazon API Gateway which calls a Lambda function to invoke the endpoint.

### Model Architecture
The model architecture used for training, validation and inference is a pretrained EfficientNetB3.

![Illustration-of-the-EffecientNet-B3-architecture-10-3646-million-weights-IRC-means](https://user-images.githubusercontent.com/44925899/236045251-8f154f49-c701-4014-9b5d-abfda0d4c5fb.png)

### Usage

This project was made for presentation purposes only since it relies on my personal AWS services.  


<!-- CREDITS -->
## Credits

Most of the web application code is open source written by Patrik Szepesi with small modifications. <br />
The usage and publishment of the code was approved by the author. 

<!-- CONTACT -->
## Contact

Alex Chagan  -- alexchagan95@gmail.com

Project Link: [https://github.com/alexchagan/TumorMedicAI](https://github.com/alexchagan/TumorMedicAI)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alex-chagan-a243221b6/







