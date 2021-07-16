# Vacuum_Chamber_Parameterization

## General Info
SketchUp's dynamic component functions allow for the parameterization of models. This allows users to modify attributes and obtain information based on those changes. The user input is handled by spreadsheet equations written in the Component Options window.

### Description of the SketchUp model
SketchUp model of the Chamber Detector/integrated beam pipe specific to Interaction Point 6. This version utilizes an equation to output the radius of the pipe at a given point. This radius can be used to determine the sizing of the outer silicon tracking layer discs.


<img width="1194" alt="Screen Shot 2021-07-16 at 2 16 40 PM" src="https://user-images.githubusercontent.com/58634750/125991591-4d1380b6-f1c4-46f5-a223-0705f339fd71.png">


## How to Use
When you open the file, you will see the Chamber Detector. Right click the component and select Dynamic Components -> Component Options. A window will appear showing the radius of the various parts and have text boxes in which you can input the respective point at which you want to find the radius. This input is the length from the inner (smaller radius) end of the part.
