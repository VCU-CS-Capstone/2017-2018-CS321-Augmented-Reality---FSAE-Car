## Project Summary
#### 	The goal of this project is understand modern capabilities of Augmented Reality (AR) technologies and how we can use AR to solve problems for, or enhance, industries. For this project, we are working with a client who is currently using Vuforia (AR SDK) and Unity, but would like assistance in coming up with creating solutions to unique problems. The most important part of working with Vuforia's SDK is understanding what its capabilities are and how we can use them. While our project consists mainly of Vuforia, you should consider other options such as Apple's ARKit and Google's ARCore. Vuforia offers several types of image targets and image objects, which can be utilized in different ways depending on the case. These types of targets include: Image Targets, Multi Targets, and Cylinder Targets. Object targets provided by Vuforia include: Object Recognition (Object Reco), VuMarks, Model Targets. Image and object targets can be differentiated by thinking of image targets as image recognition purely utilizing images and thinking of object targets as utilizing whole objects for image recognition. Furthermore, Vuforia ground plane can be used to make environments in Unity, which can then be projected onto a flat, plane surface in real life. We hope to use this document to set a path for introducing people to developing AR applications. Our goal is to get you up to speed on modern AR so that you can begin designing soultions more quickly.

#### Unity and Vuforia are extremely powerful tools for creating a variety of AR applications. In 2017, Unity and Vuforia made it much easier to create basic Augmented Reality applications by integrating Vuforia into the Unity development environment
##### To start learning about Vuforia and Augmented Reality, click [here](https://library.vuforia.com/) :point_left:
##### To start learning how to utilize the Unity development environment, you can start [here](https://unity3d.com/learn/tutorials) :point_left:
<h4 class="markdown style="bottom-margin:50px;"> If you are downloading and installing <a href="https://unity3d.com/">Unity</a>, make sure to select the option to install the Vuforia import; this will make using AR features in Unity easier.</h4>

## Getting Started
#### There are a few important things to to note starting out. You will need to create an account for Vuforia in order to link a Vuforia project with a Unity project. This key is also used as a reference to manage your image targets for your application so make sure to make a Vuforia account. Also make sure to download [Unity](https://unity3d.com/) if you haven't already. This [video](https://www.youtube.com/watch?v=Fgd21lbhikU) was super helpful in getting started and understanding how to set up an AR Camera in Unity and building/deploying an application. There are tons of videos on youtube that can help you comprehend different ways of using the unique types of targeting. Vuforia also has a 'getting started' section that you can look at [here](https://library.vuforia.com/). From there, you can find all the documentation for Vuforia.
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Fgd21lbhikU
" target="_blank"><img src="http://img.youtube.com/vi/Fgd21lbhikU/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


## Targeting Options:
### Vuforia classifies three features inside its library: Images, Objects, and Environments. We won't go into detail on all the individual types of targeting, but we talk about what to be aware of when using them. Vuforia includes user guides for all of them within their documentation as well.
#### Images: 
#### Includes Image Targets, Multi Targets, and Cylinder Targets. Image Targets all use image recognition to recognize an imamge in order to trigger an action or event to occur. That being said, its important to use images that can be recognized more easily to have greater performance from your application. Vuforia gives images a rating when you upload them to your project database; Vuforia has great documentation on this that can be found [here](https://library.vuforia.com/articles/Solution/Optimizing-Target-Detection-and-Tracking-Stability.html). Some of the basics are that you should print a picture that has these qualities: rich in detail, good contrast, lack of repetition or patters (favor randomness). You should avoid printing anything in a glossy finish as that will add a lot of glare, and try to keep images as flat as possible (no wrinkles in the paper). You will want as many features on the picture as possible; features generally come from sharp edges in the picture. Keeping this in mind, round objects in images will have no features so a picture of bubbles would have a low quality. Keep all this in mind when uploading your own images.

#### Objects: 
#### Vuforia objects includes Object Recognition, VuMarks, and Model Targeting. Object Recognition requires you to scan small objects that can be recognized, but it is very limiting for scalability (can only scan small objects). VuMarks are kind of like QR Codes, but can only be generated dynamically through the VuMark Generation API, which is only available with a Vuforia Pro account. Model targeting came out in January 2018, but can only be accessed by the upper tiers of Vuforia's licensing offerings; we were able to test it by using the 10 free tries they allow for a developer account. Model targeting is useful because it allows you to overlay a 3D object. It is less limiting than Object Recognition, but we are not sure how large the object can be. You need a physical object and the CAD file for that object to make it work which can be constraining, but it works well once you get it running.

#### Environments: 
#### Includes Extended Tracking and Ground Plane. [Extended tracking](https://library.vuforia.com/articles/Training/Extended-Tracking) solves the issue with large content being placed into the world. If the content being placed is larger than the current view of the camera, Vuforia uses Extended Tracking to allow the user to move away from the view of the image to see the rest of the content. Ground Plane is Vuforia's version of markerless targeting, known as AR Stickers in Google's ARCore and Apple's ARKit. Ground Plane detects flat surfaces where content can be placed by tapping on the screen. 

##User Guide


##Augmented Reality SDK's


##Advice
