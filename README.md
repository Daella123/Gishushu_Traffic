# Gishushu_Traffic
Gishushu traffic light state machine
GISHUSHU TRAFFIC LIGHT STATE DIAGRAM


 

In this setup, four roads (East, North, West, and South) are managed by a traffic light system. The green light rotates counterclockwise among the roads. When a road’s green light is on, all other roads display red. This green phase lasts 20 seconds. After that, the green light changes to yellow, and the next road in the cycle will be in red-yellow state as a caution signal for 4 seconds, preparing drivers for the upcoming green. 
The state diagram consists of eight states, with separate green and yellow states for each road. In the green state for any given road, only that road displays green, while the other roads show red. This green phase lasts for 20 seconds. In the yellow state, the highlighted road displays yellow, the next road in line (set to turn green) shows red-yellow as a warning, and the other roads remain red. This yellow phase lasts for 4 seconds. The states rotate in a sequence, following the pattern shown in the diagram.

STATE	   STATE NAME	   EAST	     NORTH	       WEST	          SOUTH
0	       East_Green	   Green	   Red	         Red	          Red
1	       East_yellow	 Yellow	   Red_Yellow	   Red	          Red
2	       North_Green	 Red	     Green	       Red	          Red
3	       North_Yellow	 Red	     Yellow	       Red_Yellow	    Red
4	       West_Green	   Red	     Red	         Green	        Red
5	       West_yellow	 Red	     Red	         Yellow	        Red_Yellow
6	       South_Green	 Red	     Red	         Red	          Green
7	       South_Yellow	 Red_Yellow	Red	         Red	          Yellow




