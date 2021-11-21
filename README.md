# TaiwanMaze-FreeTour

## Overview
- Two different virtual environments resembling the street views in Taiwan using Unreal Engine (Version: 4.18.3).
- Two different strategies to navigate the virtual environments: Free (free navigation) & Tour (guided video) using E-prime 2.0 software (Psychology Software Tools, Pittsburgh, PA).
- All the stimuli are in traditional Chinese as this is a Taiwan-based experiment. 
- Feel free to contact me if you want to know more about the details or if you want to translate the experiment into another language.
- A traditional Chinese version of the description will soon be added.

## Credits
- TaiwanMaze-FreeTour is co-designed by Yi-Chuang Lin, Ya-Ting Chang, and Charlotte Maschke.

***

# Table of Contents
- [Overview](#overview)
- [Virtual Environments: MapA & MapB](#paragraph1)
- [Experiment](#paragraph2)
- [Familiarization: Goal Shop Differentiation](#paragraph3)
- [Familiarization: Experimental Environment](#paragraph4)

***

# Virtual Environments: MapA & MapB<a name="paragraph1"></a>

## Stimuli
- Photographs are captured around Taipei Main Station, consisting of 55 shops, 34 walls with windows, 60 walls with doors, and 1 sidewalk pavement.
- Photographs are pasted on 3x3x3 cubic meter blank cubes to create unit buildings.
- Each virtual environment consists of 12 goal shops, 102 plain buildings, 80 roads, and 4 obstacles.
- Twelve salient goal shops are marked with eye-catching billboards.
- Screenshots of the virtual environments are captured at 1.5-m height and 120-degree field of view spaced by 6-meter distances and 45-degree orientations.
- Extra screenshots of the salient goal shops are captured with 22.5-degree orientations for direction judgment sessions during tasks.

## Mazes
- MapA and MapB are two different virtual environments with twelve distinct goal shops.
- MapA and MapB are built in a 72x72 meter square environment using 24x24 unit buildings.
- MapA and MapB are built controlling the same size and the number of the blocks, similar number of junctions, the same number of between-goal paths, similar between-goal distances, and the same non-goal surroundings. 

![Virtual_Environment](https://github.com/yichuanglin/TaiwanMaze-FreeTour/blob/main/Figures/Virtual_Environment.png)


***

# Experiment<a name="paragraph2"></a>

## Stimuli
- Background color of all the slides are black.
- All fonts are in 24-pt white bold SimHei in traditional Chinese.
- Fixations are 1x1 centimeter square white cross in the center of the screen with durations jittered from 1.5 to 2.5 seconds.
- Manipulations in the experiment should be done by the right hand using index finger as "1", middle finger as "2", ring finger as "3", and pinky finger as "4".
- Experimenter must press "5" when fixation appears after the instructions to start the experiment manually. This design is primarily meant for fMRI study as a start signal should be sent to the machine to record the accurate start time.
- Experimenter must press "q" when fixation appears after the experiment ends to exit manually.

## Learning: Free & Tour
- Four 4-minute learning sessions are provided for the participants to learn the virtual environment under either Free or Tour conditions.
	### Free
	- Participants can freely navigate the virtual environment.
		#### Location
		- Folders: MapA, MapB
		- Files to Edit: AFree1.es2, AFree2.es2, AFree3.es2, AFree4.es2, BFree1.es2, BFree2.es2, BFree3.es2, BFree4.es2.
		- Files to Run: AFree1.ebs2, AFree2.ebs2, AFree3.ebs2, AFree4.ebs2, BFree1.ebs2, BFree2.ebs2, BFree3.ebs2, BFree4.ebs2.

	### Tour
	- Participants are restricted to learning the virtual environment by watching a guided video.
		#### Location
		- Folders: MapA, MapB
		- Files to Edit: ATour1.es2, ATour2.es2, ATour3.es2, ATour4.es2, BTour1.es2, BTour2.es2, BTour3.es2, BTour4.es2.
		- Files to Run: ATour1.ebs2, ATour2.ebs2, ATour3.ebs2, ATour4.ebs2, BTour1.ebs2, BTour2.ebs2, BTour3.ebs2, BTour4.ebs2.

 ## Retrieval
- Four retrieval sessions are provided for the participants to retrieve the spatial information of the virtual environments.
	- Direction: Participants are required to choose a proximal orientation to the target goal shop.
	- Distance: Participants are required to choose a proximal distance to the target goal shop.
	- Navigation: Participants are required to navigate to the target goal shop within 90 seconds.

	### Location
	- Folders: MapA, MapB
	- Files to Edit: ATask1.es2, ATask2.es2, ATask3.es2, ATask4.es2, BTask1.es2, BTask2.es2, BTask3.es2, BTask4.es2.
	- Files to Run: ATask1.ebs2, ATask2.ebs2, ATask3.ebs2, ATask4.ebs2, BTask1.ebs2, BTask2.ebs2, BTask3.ebs2, BTask4.ebs2.

![Experiment](https://github.com/yichuanglin/TaiwanMaze-FreeTour/blob/main/Figures/Experiment.png)

***

# Familiarization: Goal Shop Differentiation<a name="paragraph3"></a>

## Stimuli
- Background color of all the slides are black.
- All fonts are in 24-pt white bold SimHei in traditional Chinese.
- Manipulations in the experiment should be done by the right hand using index finger as "1", middle finger as "2", and pinky finger as "4".

## Procedure
- First, the logos and names of twelve distinct goal shops are presented at the center of the screen in random sequence.
- Two random logos are then presented evenly spaced aside from the center of the screen, and participants are required to pair the correct name of the shop to its logo.
- The above procedure repeats itself when an error is detected and automatically ends when no error is detected.

## Location
- Folders: TargetA, TargetB
- Files to Edit: !testTargetA.es2, !testTargetB.es2
- Files to Run: !testTargetA.ebs2, !testTargetB.ebs2

![Familiarization1](https://github.com/yichuanglin/TaiwanMaze-FreeTour/blob/main/Figures/Familiarization1.png)

***

# Familiarization: Experimental Environment<a name="paragraph4"></a>

## Stimuli
- Similar stimuli are extracted from MapA and MapB.
- One salient goal shop is marked with eye-catching billboards.
- Screenshots of the virtual environments are captured at 1.5-m height and 120-degree field of view spaced by 6-meter distances and 45-degree orientations.
- Extra screenshots of the salient goal shop are captured with 22.5-degree orientations for direction judgment sessions during tasks.
- Background color of all the slides are black.
- All fonts are in 24-pt white bold SimHei in traditional Chinese.
- Fixations are 1x1 centimeter square white cross in the center of the screen with durations jittered from 1.5 to 2.5 seconds.
- Manipulations in the experiment should be done by the right hand using index finger as "1", middle finger as "2", ring finger as "3", and pinky finger as "4".
- Experimenter must press "5" when fixation appears after the instructions to start the experiment manually. This design is primarily meant for fMRI study as a start signal should be sent to the machine to record the accurate start time.
- Experimenter must press "q" when fixation appears after the experiment ends to exit manually.

## Maze
- A smaller virtual environment is built in a 24x24 meter square environment using 8x8 unit buildings.

## Learning: Free & Tour
- One 4-minute learning session is provided for the participants to learn the virtual environment under either Free or Tour conditions.
	### Free
	- Participants can practice navigating the virtual environment freely.
		#### Location
		- Folder: Practice
		- File to Edit: PFree.es2
		- File to Run: PFree.ebs2

	### Tour
	- Participants can practice learning the virtual environment by restricting to watching a guided video.
		#### Location
		- Folder: Practice
		- File to Edit: PTour.es2
		- File to Run: PTour.ebs2

 ## Retrieval
- One retrieval session is provided for the participants to practice retrieving the spatial information of the virtual environments.
	- Direction: Participants are required to choose a proximal orientation to the target goal shop.
	- Distance: Participants are required to choose a proximal distance to the target goal shop.
	- Navigation: Participants are required to navigate to the target goal shop within 30 seconds.

	### Location
	- Folder: Practice
	- File to Edit: PTask.es2
	- File to Run: PTask.ebs2

![Familiarization2](https://github.com/yichuanglin/TaiwanMaze-FreeTour/blob/main/Figures/Familiarization2.png)
