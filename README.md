# Facial Recognition based Attendance

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run train.py file

**Technology used :**
->openCV (Opensource Computer Vision)
->Python
->tkinter GUI interface

Hello guys...

Here I am working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply showing their face on camera. 

**How it works :**

We need to first run `train.py` , a window is opened and ask for `Enter Id` and `Enter Name`. After entering name and id, click `Take Images` button. By clicking `Take Images` button, the camera of the current computer is opened and it starts taking image samples of the person. This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 60 images as sample and stores them in the folder TrainingImage. After completion it notifies `Images saved`.
After taking image samples we have to click `Train Image` button. Now it will take a few seconds to train the machine and creates a Trainner.yml file and stores it in TrainingImageLabel folder.
Now all initial setups are done. By clicking `Track Image` button, the camera of the current machine is opened. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) to quit this window. After quitting it attendance will be stored in Attendance folder as csv file with name, id, date and time.

**Steps to install**

Type in `pip install -U -r requirements.txt`

To Start the application type in `python train.py` 

-S. B. John
