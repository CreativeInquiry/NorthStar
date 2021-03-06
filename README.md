# North Star
Information about the STUDIO's North Star AR headset.

The project is the work of CMU North Star Institute (Active from Fall 2018 - Fall 2019) - Gray Crawford, Cameron Burgess, Xiangyu Sun, Gautam Bose, Lucas Ochoa, Yuzin Ariza, Marisa Lu - Funded by a FRFAF Grant from the STUDIO and project grant from the CMU Entertainment Technology Center.

# North Star Setup

1. Download and extract this repository 
2. Open `Unity Project - North Star & Vive Tracker` in Unity


## Importing the display calibration file for your North Star hardware
1. Your North Star hardware number is on the rear of the left display with a Roman numeral
2. Under the `North Star + Leap Motion` game object, select the `ARCameraRig` game object
3. Under `Optical Calibration Manger` component, change *Input Calibration File* to ’NS-X.json’ where X is the Arabic number of your headset
	 - All North Star calibration files are located within `Assets / CalibrationFiles`

## Setting up 6-DOF tracking with Vive Tracker 
1. Turn off all Vive Controllers, only the Tracker should be connected
2. Select `North Star + Leap Motion` game object
	 - Under `Steam VR Tracker` component, set *Device ID* to 1


# Other

## Customizing the Leap Motion’s relative transform
1. Navigate to the game object `North Star + Leap Motion` → `AR CameraRig` → `Head` → `Leap Provider`
2. Within the `Leap XR Service Provider` component, under advanced, you can set *Device Offset Mode* to Default, Manual Head Offset, or Transform


# Helpful Links
 - [North Star Project Overview](https://leapmotion.github.io/ProjectNorthStar/)
 - [North Star Project Repository](https://github.com/leapmotion/ProjectNorthStar/)
 - [North Star Discord Community Forum](https://discord.gg/ATPm9Fy)
 - [Camera Calibration Video Instructions](https://www.youtube.com/watch?v=twyUk7MtiHo)
 
 # Calibration Files
 - [STUDIO Headset](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/STUDIO.json)
 - [ETC Headset 1](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/NS-1.json)
 - [ETC Headset 2](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/NS-2.json)
 - [ETC Headset 3](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/NS-3.json)
 - [ETC Headset 4](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/NS-4.json)
 - [ETC Headset 5](https://github.com/CreativeInquiry/NorthStar/blob/master/north%20star%201/Assets/CalibrationFiles/NS-5.json)
