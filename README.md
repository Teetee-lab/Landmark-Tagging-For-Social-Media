# Landmark Tagging For Social Media

![World-Countries-image from google-istockphotos](https://github.com/[Teetee-lab]/[Landmark-Tagging-For-Social-Media]/tree/[main]/sample-img/wrldlandmark.jpeg)

## Project Overview

Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernable landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo-sharing services, using human judgment to classify these landmarks would not be feasible.

In this project, I address this problem by building a CNN-powered app to automatically predict the location of the image based on any landmarks depicted in the image. Aside from that I developed an application that will accept any user-supplied image as input and suggest the top most relevant landmarks from 50 possible landmarks from across the world.

## Outcome

Built a Convolutional Neural Network Model from scratch and a pretrained model (RESNET) to train the dataset. 

## How to use the app

Install the requirements of the project:

    ```
        pip install -r requirements.txt
    ```
Install and open Jupyter Lab:
	
	```
        pip install jupyterlab
		Jupyter lab
	```

## Dataset Info

The landmark images are a subset of the Google Landmarks Dataset v2. 

## Repository Structure



  	├── sample_image_folder    <- contains a sample images to test the application
  	├── src    <- The folder contains all Python file used for the project
  		├── _init_.py             
  		├── data.py           <- dataloader python file
   		├── create_submit_pkg.py 
    	├── helpers.py <- helper python file
     	├── model.py <- build a CNN model python file
      	├── optimization.py <- model optimization python file
       	├── predictor.py <- model predictor python file
		├── train.py <- model training python file
 		├── transfer.py <- transfer learning python file
  
  	├── app notebook and app HTML     <- Jupyter notebook and HTML link to test sample images
  	├── Cnn_from_scratch notebook and HTML file     <- This is a Jupyter notebook or HTML file where I test the source Python files
  	├── requirement text file     <- This is the requirement text file that needs to be installed locally in order to run the app and notebook
  	├── transfer_learning notebook and HTML file     <- This is a Jupyter notebook or HTML file where I test the source Python files
  	├── gitignore <- the file holds untracked files
  	└── README.md            <- Top-level README

  ## Author

  Titilayo Amuwo
