# Bear Coin Bank

### Short description
The mechanism that I chose for the final project is a bear coin bank. When inserting coins, the bear's mouth opens and the coin slips inside the bank. I chose this project because it's both useful and adorable.

### How it works
<a href="https://www.youtube.com/watch?v=njh3S9VZ788&t=255s">
<img src="https://user-images.githubusercontent.com/76184859/115960332-72940200-a519-11eb-92a5-eea48b61f87a.gif" alt="Source: https://www.youtube.com/watch?v=njh3S9VZ788&t=255s" width="400"/>
</a>

The bear coin bank works by pushing the bear's ears, which elevates the hand with the tray, and the coin slips inside the bear's mouth. The coins can be collected by opening the bottom cap.

### Components
* body;
* head;
* arm;
* eyes;
* jaw;
* bottom cap;
* arm slide;
* left spring;
* right spring.

### Joints

For the main motion I created 3 joints:
* Head - Body (Revolute);
* Slider - Body (Slider);
* Arm - Body (Revolute).

I added 2 motion links between these joints, named _Head-Slider_ and _Slider-Arm_. When the _Head_ rotates, it pushes the _Arm Slide_ component.  
The _Arm Slide_ pushes the end of the _Arm_ and determines its rotation. The _Head-Slider-Arm_ motion study shows how this motion works.

https://user-images.githubusercontent.com/76184859/119259722-35826480-bbd8-11eb-92a2-ba6e3ec79650.mp4
<p>&nbsp;</p>

For the cap motion, I added a Cylindrical joint named _Cap-Body_. 
I created a _Cap_ motion study: the cap rotates to 90 degrees and then it slides down. The reverse motion is used to close the cap.


https://user-images.githubusercontent.com/76184859/119259893-028ca080-bbd9-11eb-88d8-5b859e7ca01a.mp4
<p>&nbsp;</p>

I created another .f3d file named _Demo_, which shows how the coin is inserted inside the bank.
It contains all the components and motion features as the main project, and besides them, I added a _Coin_ component, a pin-slot joint named _Coin-Body_ and a motion study that shows the relation between the _Head-Body_ and _Coin-Body_ joints.
  

https://user-images.githubusercontent.com/76184859/119260120-066cf280-bbda-11eb-9f37-cb27952eca80.mp4

#### Finished mechanism

<img src="https://user-images.githubusercontent.com/76184859/119263103-6073b500-bbe6-11eb-8347-c336a9585d17.png" height="300">  <img src="https://user-images.githubusercontent.com/76184859/119263106-623d7880-bbe6-11eb-8edc-db6b65a43bb6.png" height="300">  <img src="https://user-images.githubusercontent.com/76184859/119263181-adf02200-bbe6-11eb-922f-f52303e3a044.png" height="200">


### Checkpoints
##### Checkpoint 1:
- chose project;
- created main components.

##### Checkpoint 2:
- decided to model a cat coin bank instead of a bear coin bank;
- created the body;
- started designing the head and the eyes.

##### Checkpoint 3:
- finished the head, eyes and mouth;
- added appearance.

##### Checkpoint 4:
- finished all components;
- added joints, motion links, motion studies;
- created a demo project;
- rendered the mechanism;

### Renderings
The renderings were made in the _Demo_ file. I used the _Rim Highlights_ environment.  
  
<img src="https://user-images.githubusercontent.com/76184859/119263997-01b03a80-bbea-11eb-98ab-3135b9f1154b.jpg" height="300">  <img src="https://user-images.githubusercontent.com/76184859/119263999-02e16780-bbea-11eb-85cc-389e6c1dfe1e.png" height="300">  <img src="https://user-images.githubusercontent.com/76184859/119264000-04129480-bbea-11eb-9201-0b3e5260598e.png" height="300">

<img src="https://user-images.githubusercontent.com/76184859/119262780-2c4bc480-bbe5-11eb-9be9-bf5dd755f143.gif" width="450">  <img src="https://user-images.githubusercontent.com/76184859/119265806-ac2b5c00-bbf0-11eb-9010-8b9fc6f42f0f.gif" width="450">

### Mechanism's author
Thingiverse: https://www.thingiverse.com/thing:4809969  
Youtube: https://www.youtube.com/watch?v=njh3S9VZ788&t=255s

I used [this cat](https://www.instagram.com/milkyblvck/) as an inspiration in designing the cat coin bank:  
  
<img src="https://user-images.githubusercontent.com/76184859/119265907-3a074700-bbf1-11eb-8436-af20a77dc07a.png" height="400">


### Software and files
The software I used to create and render this project is _Fusion 360_. The whole project is saved as an _.f3d_ file and each body is saved as an _.stl_.  
Other file types: .png, .jgp, .mp4, .gif.

