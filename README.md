# Autonomous-Driving-System
An autonomous driving car simulation with the help of CNN model.
## About the project
The project is about building a simulated version of self-driving car in a 3D environment. Here, we will first drive the car manually and gather the front, right and left camera view of a simulated car. We would also record the steering angle, throttle and break information. This data will be fed through the Convolutional Neural Network and the label will be the focal point for the images. Then the CNN model on the computer will learn the steering angle from the training data and will eventually predict the steering angle throttle and break of the unknown images, to make the car drive by itself and avoid all kinds of collisions/deviations from the track.
![image](https://user-images.githubusercontent.com/86741118/163034172-b79b8b4d-410b-46e9-92e9-7c49715a12e9.png)
## Procedure for running the project
1) If you just want to run this project, then download this repository.
2) Install anaconda.
3) Downlad the Car simulator from following link: https://github.com/udacity/self-driving-car-sim, this is basically a simulator specifically built for testing self driving cars.
4) Now open the anconda prompt and navigate to this project folder.
5) Now type the following command: python drive.py modelpresent.h5
6) This should start the server.
7) Now open the udacity simulator and choose the autonomous mode.
8) The car shall be driving on its own.
## Procedure for building the model
1) To begin we you need to have anconda and Car simulator from following link: https://github.com/udacity/self-driving-car-sim.
2) Now we have to open the simulator and select training mode.
3) Now press the R button to start recording and drive the car with arrow key.
4) This will start the capturing of data.
5) After you are done press R again to stop recording.
6) You shall have a IMG folder with images in it and driving_log.csv file.
7) Move them both to a new folder named "data" and compress it.
8) Now open google collab and upload the compressed folder.
9) Now use the code from ModelGenerationPIVAMO.ipynb of the repo and generate the modelpresent.h5 file, this is the CNN model for driving the car.
10) Now just use this file and follow the instructions above for running the project.
## Screenshots
1) Model Generation from dataset:
![image](https://user-images.githubusercontent.com/86741118/163038669-0871f313-6d41-42dd-85bf-9a6671ecf420.png)
2) Typing command in anaconda prompt:
![image](https://user-images.githubusercontent.com/86741118/163038905-4ae71e17-efde-403c-8033-04111938ceda.png)
3) Autonomous car in action:
![image](https://user-images.githubusercontent.com/86741118/163039283-f8982c02-b1b1-47b9-8128-d409f3352240.png)
