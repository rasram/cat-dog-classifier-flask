# Cat and Dog Classifier using Flask and Docker

This project involves developing a web application using the Flask framework, which is then containerized and deployed using Docker. The Docker setup ensures that the application is portable.

## Instructions

2. Download the model from the link below in the resources section
3. Move the downloaded model to the weights folder and replace the "best_model.h5" file inside
4. Run the following commands
   
   ```
   docker build .

   docker run -p 5000:5000
   ```
5. Go to http://127.0.0.1:5000/upload in your web browser.
6. OR using the docker pull command to pull and directly deploy the Flask app from the Docker Hub page in Resources

## Resources
H5 model link: https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5

Docker Hub Page: https://hub.docker.com/repository/docker/tarotsun/cat-dog-classifier/general

## Demo

[2f33adc3-dca6-4dec-8a77-b38f40c39c68.webm](https://github.com/rasram/cat-dog-classifier-flask/assets/97001864/ce38f079-403e-4c7c-994e-838e8c0d2a4c)


