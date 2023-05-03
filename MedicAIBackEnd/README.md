

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

 
### Tumor Detection AI Backend


![Image10](https://user-images.githubusercontent.com/44925899/235746366-3271d9cb-ddb8-4143-bc4f-9625646de109.jpg)

<!-- ABOUT THE PROJECT -->
## About The Project
A Backend infrastructure for an AI image classification project for detecting tumor in MRI images. <br />
The classifier and endpoint were created using the SageMaker AWS service and documented in the notebook file. <br />
The backend makes requests to an AWS API Gateway which uses a Lambda function to invoke the endpoint.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Installation

1. git clone or download zip
2. Navigate to root directory
3. Create .env file in root directory
4. Add the following to the .env file:
   ```
   PORT=8000
   DATABASE=enterYourMongoDBStringWithUsernameAndPassword
   JWT_SECRET=LKAJSDFHJKS"+!%SDFG345+!%/GSDFGSDFG345
   ```
5. Run the command ```npm install``` in your terminal from the root
6. Run the command ```npm run start```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Alex Chagan  -- alexchagan95@gmail.com

Project Link: [https://github.com/alexchagan/sports-images-classifier](https://github.com/alexchagan/sports-images-classifier)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alex-chagan-a243221b6/







