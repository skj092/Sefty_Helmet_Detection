# Sefty_Helmet_Detection

`Codes:` https://drive.google.com/drive/folders/1-L2Mzz5-u91SKeV4pMdN4XyrjlrUQ2xq?usp=sharing

`Aim:` To build an object detection model which can detect whether person on the construction site is wearing helment or not. 

`Model Architecture:` I have used YOLOv5 for the task, model will be used on the construction site for the live video frame so need an architecture which can run on higher fps. 

`Result:` I have trained the model for 100 epoch which give the following result: 

![image](https://user-images.githubusercontent.com/43055935/200990256-8ea99519-2398-4c28-a63f-d6aca0cfb168.png)

Model is evaluated on the video : https://www.youtube.com/watch?v=6PoPwZ0WO9w 

result video named "output.mp4" can be found in the drive link. https://drive.google.com/file/d/1-8EFQ0I_bI_ixhDv4fYKWJFvTx7_aqe6/view?usp=share_link 

We have also evaluated on the 250 test images and the result is "[test-img-and-result](https://drive.google.com/file/d/1N77vzpRaWDoGBPFNmDZkuvfchG5PQbN3/view?usp=share_link)" 

![Output Video](https://github.com/skj092/Sefty_Helmet_Detection/blob/main/output.gif)
