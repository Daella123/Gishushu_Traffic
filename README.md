# Gishushu_Traffic
Gishushu traffic light state machine
GISHUSHU TRAFFIC LIGHT STATE DIAGRAM


 

In this setup, four roads (East, North, West, and South) are managed by a traffic light system. The green light rotates counterclockwise among the roads. When a road’s green light is on, all other roads display red. This green phase lasts 20 seconds. After that, the green light changes to yellow, and the next road in the cycle will be in red-yellow state as a caution signal for 4 seconds, preparing drivers for the upcoming green. 
The state diagram consists of eight states, with separate green and yellow states for each road. In the green state for any given road, only that road displays green, while the other roads show red. This green phase lasts for 20 seconds. In the yellow state, the highlighted road displays yellow, the next road in line (set to turn green) shows red-yellow as a warning, and the other roads remain red. This yellow phase lasts for 4 seconds. The states rotate in a sequence, following the pattern shown in the diagram.





