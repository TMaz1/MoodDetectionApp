<h1>Mood App</h1>

This project was a collaboration with a total team of four people in 2019/20. 

The project extended a currently existing mobile application.

As the app is existing and the extensions of the app were made for the purpose of a project, only the necessary files used in the collaborative project are added to this repository. 

- The repository for the full application can be seen here: https://github.com/CMDT/gaddum_app. 
- You can find more information about the application at https://cmdt.github.io/gaddum/.

<h3>Application Summary</h3>

The app uses facial recognition, from the front-facing camera, to depict the user’s mood and plays a playlist depending on said mood.

This is Ionic + Cordova crossplatform mobile app using AngularJS and the jeelizFaceFilter JavaScript library (https://github.com/jeeliz/jeelizFaceFilter). The Jeeliz FaceFilter API provides facial detection and movement using JS, Python and neural networks. Parameters of person's facial feature when experiencing each mood are defined. 

The following moods:

0 : PHYSICAL <br>
1 : TIRED <br>
2 : ANGRY <br>
3 : PEACEFUL <br>
4 : FOCUSSED <br>
5 : BORED (AIMLESS) <br>
6 : HAPPY <br>
7 : SAD <br>
8 : CRAZY <br>
9 : RESTFUL

Only one dominant mood dimension is pulled from the set and an emoji displays to reflect detected mood to user.

<h3>Goal of Project</h3>

Improve the mood recognition user experience and enhance the facial recognition function.

<h4>Old version mood recognition user experience: </h4>

  -   No camera feedback: so users could not see if their face was in frame for the camera to identify their facial expressions.
  -   Character/emoji displayed to the user that represents the final detected mood of the user.
  -   Less accurate parameters to identify mood from a user's facial expressions.

<h4>The mood recognition user experience was successfully improved by: </h4>

  -   Having a heavily blurred camera feedback area: the user can see if their face is in frame without having to feel self-conscious.
  -   A grey-scale character/emoji is displayed during the process of identifying the mood of the user.
  -   When the mood is detected from a user's facial expression, a colour character/emoji representing their mood is displayed.
  -   The mood recognition process and parameters are set to be more accurate for the users.

