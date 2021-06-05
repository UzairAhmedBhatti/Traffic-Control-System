# Traffic-Control-System

Traffic Light Controller
You have to design traffic controller for DLD Square. The configuration of Square is given below.
 
There are total four roads. Each road has two partitions, one for the traffic coming towards the square (trafficIn) and the other one for traffic going out of the square (TrafficOut). Each partition has three lanes. The cars at right most lane go on the road at right side. The cars in middle lane go straight. The cars in left most lane go on the left side of road. Your task is to implement a system with following requirements:
1-	System should show the flow of cars
2-	Cars will randomly come on TrafficIn partitions
3-	Each lane can have 15 cars at max and you need to display only 4 cars per lane
4-	There is one traffic signal per road for trafficIn. TrafficIn will stop if the signal is red and start running when it turns green
5-	Four signals (one per road) run clockwise i.e. road 1’s signal will be green at start, then road 2’s then road 3’s, then road 4’s and then again road 1’s signal will be green
6-	Each signal remains green for 16 ticks at max or until there is no car on that road
7-	Signal will turn yellow for 4 ticks before turning red
