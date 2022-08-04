# REU_2022Summer_NewInteractionForMRCANE
![REU_NSF_logo_with_title_transparent_background](https://user-images.githubusercontent.com/63988329/182754909-0fa66a5a-2ce3-4635-834c-5c2e116cc197.jpg)
<br>
![hunter-2x](https://user-images.githubusercontent.com/63988329/182761768-4d708cff-6072-40c7-9d25-d6e1495613d3.png)
<br>
## Design an effective gesture based user interface for MR cane
- Laser pointer
- Gesture menu

## Laser pointer
The laser pointer is a pen-shaped pointing device with a quick look-around mode that can emit an intense beam of the ray cast
The iPhone's rear camera is used to obtain the estimation of the camera pose, which is used to control the laser pointer. Compared with the virtual cane, the length of the laser pointer is not fixed, and it can interact with any object at different distances in the room. The user can obtain the voice broadcast of the attributes and spatial information of the object pointed by the laser pointer.


## Gesture menu
The Gesture Menu is the new User Interface of Mobile AR.
Through the camera's pose displacement tracked by the rear camera, we can obtain the changes in the direction and distance of the camera. When the camera's pitch rotation is larger than 90 degrees, the gesture menu will be turned on and while the menu is on, the current option of the gesture menu will move to the next item automatically every two seconds. And if camera’s pitch rotation is small than 90 degrees, the menu will close and the currently selected item will be activated.


## Requirements
- Unity 2021.2.2f1
- Xcode 13.4.1
- macOS Monterey 12.4 

## Acknowledgments
This project was created with the help of the following contributors
- Director: [Dr. Wole Oyekoya](https://wolex.com/reu/)
- Mentor: [Dr. Hao Tang](https://www.bmcc.cuny.edu/faculty/hao-tang/)

