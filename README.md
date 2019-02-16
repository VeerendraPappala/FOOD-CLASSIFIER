# FOOD-CLASSIFIER
Image classifier to identify 9 types of Mexican foods

Mexican cuisine is one of the most popular ones in the world. This Project is to identify different types of mexican foods by looking the image. 

## Mexican Food Dataset
 
Use the Google Images Download library. A Python Script for 'searching' and 'downloading' hundreds of Google images to the local hard disk!. 

You can use this library with the following instruction:

pip install google_images_download #Installing the package

from google_images_download import google_images_download #importing the library

response = google_images_download.googleimagesdownload() #class instantiation

arguments = {"keywords":"Polar bears,baloons,Beaches","limit":20,"print_urls":True} #creating list of arguments paths = response.download(arguments) #passing the arguments to the function print(paths) #printing absolute paths of the downloaded images

I collected images using this library and uploaded a food dataset to Google Drive.

## This project is to identify 9 different kind of mexican food dishes:

Aguachile
Callos de Hacha
Ceviche de Camarón
Ceviche de Sierra
Chilaquiles
Coctel de Camarón
Tacos Gobernador
Pozole
Pescado Zarandeado

Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. I uploaded the dataset to Google Drive, so you can download it directly. 


You can read a paper implementing the same idea [here](https://arxiv.org/ftp/arxiv/papers/1612/1612.00983.pdf)
