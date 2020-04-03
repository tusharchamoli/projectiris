# projectiris

How To Use
1.	Install IRIS app in your android smart phone.
2.	Copy the python code folder on the raspberry pi, with a working operating system and install all the required dependencies - Python, openCV, DLib.
3.	Connect a Bluetooth headset to android phone which has IRIS app installed and open IRIS app by using the buttons of headset.


Computer Vision aided wearable device for Visually Impaired with Smart Voice Assistant
 
Lakshya Gupta(Student UPES, Dehradun)  
Megha Gupta(Student MRIU, Faridabad)

Jai Gupta(Student UPES, Dehradun)  
Tushar Chamoli(Student UPES, Dehradun)   
 
“Computer vision can now really be Someone’s Vision”
 
Abstract
Computer vision is a technology which uses cameras, to help a machine understand any visual input in front of it. This technology has been around for enough time and is being used in almost all expects of a person’s life. Also in field providing a visual alternative for visually impaired, a significant work has been done, which is also the focus of this paper. It’s sad that these advancements never came to reality. Because of many technical, economical as well as social reasons.
IRIS- app and device is an attempt in the direction to make use of Computer vision and many such technologies to make a significant change in lives of visually impaired people. The following paras describe working of the same.
Introduction
IRIS device is a wearable pair of glasses, having a camera attached in front of it. The camera captures real time feed of the scene in front of the person 

wearing the device. Then the device processes the image for various parameters like faces, texts, objects, colours. Analyses each parameter on different globally 
Another problem faced by visually impaired is the access to technology, in this era when users are getting completely depended on technology to do each part of their day to day chores. Those without the ability to see the screens or control touchscreen get excluded from most of the technologies, solutions. A completely human task like listening to songs becomes difficult. Here comes the second part of our solution IRIS-Device and app. We aim to provide a completely voice controlled OS-like system to control features of a smartphone, combined with the IRIS device, A person would be able to use any feature of his smart phone without taking his/her phone out of the pocket. With the proposed solution a visually impaired person can use Features like calling, messaging, listening to songs, browsing net, booking cabs, using navigation and doing almost everything likewise with a sense of individuality and self-respect.
 
Flowchart










 
Procedures (materials and methods)
 

 
Fig 3 : More accurate and stable version 





 
Technologies used
•	Android – Android app is used for sending and receiving audio input and output from the firebase.
•	Google now- Google now is used for basic features of smart phone like calling, listing music, booking cab and many more.
•	Text to speech – Text to speech api is used in the android app to convert the output text that is received from firebase to audio that is sent to the user.
•	Speech to text – Speech to text api is used in the android app to convert the audio of  the user to text that is send to the firebase for further processing.
•	Firebase – Firebase is used for the linking of python and android app. It receives the output from the python codes and send it to android app and vice versa.
•	Python – Python used for implementing the image processing using the Microsoft cognitive services api. After analysis it send the output to firebase for further analysis.
•	Microsoft cognitive services – This is used for image analysis.
•	Computer Vision – It is based on a computer image analysis in real time when images for analysis are supplied by camera. The possibilities of this technology are nearly unlimited and they reach into various areas. Using computer vision can help you extract a lot of information regarding the environment using just a simple camera. 
Devices Used
•	Android Phone – Android phone is used to access our app and other apps.
•	Bluetooth Headset - Bluetooth headset is used to control our android app and Google now. It is also used to send the audio input to our app and receiving the audio output from our app.
•	Camera - Camera is used for clicking the pictures of the objects and sends it to raspberry pi for further processing. 
•	Raspberry Pi - Raspberry pi is used for image processing and to run our python codes. 
 


