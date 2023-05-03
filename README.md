# MNIST

<img src="https://github.com/Mukhriddin19980901/MNIST/blob/main/pics/mns.png" width="700" height="500" />

# Introduction.
In order to use this model you need to create the environment on you computer.This is a Keras easy type data for beginners of Computer Vision.
Data consists of 10 different types of images in both train and test data.Each type has around 5000 images of total 60,000 28x28 pixel images in train data .Another 10,000 in test data.I used CNN model.  


# Step - 1 . Downloading model

- First click the buttons *windows+R*  and type *cmd* in box below clone my model from github on the black window

       C:\>  git clone https://github.com/Mukhriddin19980901/MNIST.git

- Write this command on black window.
 
       C:\> cd MNIST
 
# Step - 2 .Creating virtual environment 

- You need to upgrade your pip command to create environment

       C:\MNIST>python.exe -m pip install --upgrade pip


- Here you need to install environment module and you can create  your virtual environment

       C:\MNIST>python -m venv pip install --user virtualenv
 
 - Give the name to the environmentyou can give any name instead *environment_name*)

       C:\MNIST>python -m venv environment_name

- Then you need to activate the environment

       C:\MNIST>environment_name\Scripts\activate.bat

- Install all required libraries from the *requirements.txt* file

      (environment_name) C:\MNIST> pip install -r requirements.txt

- Now you can work on jupyter notebook

      (environment_name) C:\MNIST>jupyter notebook


# Step - 3 . Coding

- You can see the classes of the data  :

<img src="https://github.com/Mukhriddin19980901/MNIST/blob/main/pics/mnist2.png" width="700" height="500" />
 
- Now you can see the code [here](https://github.com/Mukhriddin19980901/MNIST/blob/main/MNISTdata.ipynb).The model was built on CNN.

- The model accuracy is perfect for this project which is about 99 % percent for validation.


<img src="https://github.com/Mukhriddin19980901/MNIST/blob/main/pics/mnisthist.png" width="700" height="500" />



- [Here]() is a notebook for  deploying the model 

🔴 ***If you find it useful give a star to this repo and follow me on [Kaggle](https://www.kaggle.com/muhriddinmalik) and [Linkedin](https://www.linkedin.com/in/mukhriddin-khaydarov-8a9729209?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bay%2BB1xqoRZKf2DcZnvkRVw%3D%3D)***
