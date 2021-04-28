# Rise of The Magni

## Gameplay

![image](https://user-images.githubusercontent.com/13844325/116411318-b5433a80-a889-11eb-9195-92de196b748f.png)

Two players each select exactly 10 Hero Units to compete against each other. Both players select a Lead Unit to fight for the center of the map, and then take turns to place units around the map to score points. Once the map is full (19 units have been placed), the winner is the player with the highest score.

## Fighting for the center

Your Lead unit will determine if you play first or second. Each player selects a single unit to control the center of the map. The unit with the higher Center Attack Value (CAV) is deemed the winner and takes control of the center of the map and becomes Player 1. The losing unit is placed directly above this. Players then take turns placing units.

![image](https://user-images.githubusercontent.com/13844325/116411157-8cbb4080-a889-11eb-93c0-539234ad06fe.png)

## Scoring - Skirmish and Fortifications

Points are scored by winning Skirmishes (edges of a hexagon) and making Fortifications (corners of a hexagon). 

A Skirmish occurs when two adjacent units from oppossing players a placed. The unit with the higher corresponding attack value (LAV, CAV or RAV) wins the skirmish and is awarded a point. No points are awarded in the case of a draw. See below:

![image](https://user-images.githubusercontent.com/13844325/116411528-eae82380-a889-11eb-9502-1ae372bcf9d5.png)

A fortification is created when 3 allied units are placed adjacent to each other around a single point/corner, and is awarded a point. See below:

![image](https://user-images.githubusercontent.com/13844325/116411465-db68da80-a889-11eb-8226-cdccd16fdaf4.png)

**Note: The only Skirmish that is not awarded a point is between the Lead units placed by each player when taking control of the center.**

## Hero Unit

Each unit contains the following elements:

  - A *Unique Name*
  - A *Rating* from 1 to 4, where higher numbers reflect stronger units
  - The attack values correspond to the 6 sides of a hexagon
    - *Left Attack Value/LAV* for the **NW** and **SW** edges
    - *Center Attack Value/CAV* for the **N** and **S** edges
    - *Right Attack Value/RAV* for the **NE** and **SE** edges

In future, Hero Units will contain more attributes to assist with more strategic gameplay.

## Team Composition

A team is made up of 10 Hero Units with a maximum accumulated rating (Team Rating) of no more than 23. This restriction provides a balancing factor to allow for more strategic gameplay.
