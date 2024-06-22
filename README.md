# Cat and Dog Classifier using Flask and Docker

Cat and Dog Classifier using an H5 model. Flask is used to create the web page and Docker to containerize the project.

## Instructions

1. Git Clone repository
2. Download the model from the link below in the resources section
3. Move the downloaded model to the weights folder and replace the "best_model.h5" file inside
4. Run the following commands
   
   ```
   docker build -f Dockerfile -t cat-dog-classifier-using-flask .

   docker run -p 5000:5000 -d cat-dog-classifier-using-flask
   ```
5. Go to http://127.0.0.1:5000/upload in your web browser.

## Resources
H5 model link: https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5

Docker Hub Page: https://hub.docker.com/repository/docker/velvett/cat-dog-classifier-using-flask/general

## Demo

https://github.com/VelvetThunder1/Cat-and-Dog-Classifier-using-Flask-and-Docker/assets/74422927/58f1786c-0288-4825-a44b-3efa6d8bc994

