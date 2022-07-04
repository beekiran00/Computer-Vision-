# Computer-Vision-
Image Similarity using CNN and Keras
The main working model is Keras CNN 
CAE is a work in progress to implement autoencoders

# Links to Datasets

http://ai.stanford.edu/~jkrause/cars/car_dataset.html#:~:text=Overview,or%202012%20BMW%20M3%20coupe.


# How to Use

## 1 The file path has to be chaned on the img_folder 

![Screenshot 2022-07-04 at 9 32 04 am](https://user-images.githubusercontent.com/63056373/177115428-67bab09e-d2df-403b-b862-2b51effc5826.png)

By changing the file path, you get to choose which dataset you're working on. 

## 2 In the Main function the numbers at the result and input_show has to be below the number of files in the dataset.

The splits of how much you want to train the model, goes in the for loop

![Screenshot 2022-07-04 at 9 34 45 am](https://user-images.githubusercontent.com/63056373/177115980-dd1001f7-a49c-4b02-8e6e-63ccda5c21b6.png)

The output is a grid of 12 images that are similar to the query image for example:

<img width="341" alt="Screenshot 2022-07-04 at 9 08 54 am" src="https://user-images.githubusercontent.com/63056373/177116151-e8db7d27-e0fa-4ec5-aa9d-dc9587754421.png">

<img width="746" alt="Screenshot 2022-07-04 at 9 09 05 am" src="https://user-images.githubusercontent.com/63056373/177116171-0efe8b12-3290-489c-81ca-730150e1901a.png">

<img width="709" alt="Screenshot 2022-07-04 at 9 09 14 am" src="https://user-images.githubusercontent.com/63056373/177116181-fe9d528d-3aae-446f-b6c4-0d2407b5224f.png">
