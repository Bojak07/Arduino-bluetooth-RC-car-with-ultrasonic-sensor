<h1>In this project, you build a radio-controlled car with two wheels that is controlled using RemoteXY</h1>

<img width="400" height="225" alt="WIN_20260513_13_25_19_Pro-ezgif com-optimize" src="https://github.com/user-attachments/assets/8768c470-67b4-4fa9-9c60-cbe32da69f81" />
<img width="400" height="225" alt="WIN_20260513_13_25_19_Pro-ezgif com-optimize (1)" src="https://github.com/user-attachments/assets/10bf99c7-7483-4563-a222-782498100d4f" />
<h2>Components and sensors</h2>

This project uses and is adapted to use an Arduino R4 wifi (Bluetooth BLE), an L298N, two geared dc motors with wheels, six series connected AA batteries and an Ultrasonic sensor (HC-SR04) as well as a 3-D printed cover for the car.

<h2>Connections</h2>

<img width="800" height="400" alt="Tinkercad_Image.png" src="Skärmbild 2026-05-14 174317.png" />

Above image shows connections and couplings. Tinkercad does not have these components in the project: Arduino R4 Wifi, L298N, HC-SR04 or six series connected batteries. A compromise was made and had to use instead: Arduino UNO R3, L293D, Parallax PING and four batteries connected in series.  

<h2>Setting up RemoteXY</h2>

In order to be able to control the car, you use RemoteXY to create the GUI and then use the corresponding app in the mobile phone. Create GUI in RemoteXY web page. You can use different components to design your GUI. Then either copy or download the GUI source code that RemoteXY gives you. The GUI code must then be integrated with the code for the car itself. This code must then be uploaded to the Arduino. You can write your own code for how the car should work.

Then download and open the RemoteXY app in the mobile phone. When the code is running in the car, you should be able to choose to connect via bluetooth to the car in the RemoteXY app. When you are connected, you should be able to see the GUI you made and be able to control the car from there. Don't forget that Bluetooth must be on your mobile phone for it to find and pair with the car.
