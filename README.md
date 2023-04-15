# MyMap
This is my map software developed using C++. It serves as the background for my LinkedIn profile and was created through a collaboration with Fabien, one of my close friends at the University of Toronto.

## Contest 3rd place
This project entered the Courier Problem Contest(A special case of the Traveling Salesman problem) and won third place thanks to the clever use of Simulated Annealing heuristics and parallel programming. The contest consists of more than 80 teams and 74 valid submissions, this contest is open to all Electrical and Computer Engineering students.
### Team Number
<img width="908" alt="Team Number" src="https://user-images.githubusercontent.com/37476565/232179376-0df8dfe6-6cc5-4245-bc04-301f410041dd.png">

### Overall Ranking
<img width="888" alt="Overall Ranking" src="https://user-images.githubusercontent.com/37476565/232179594-2519e24a-2c90-421a-a031-867495abfc29.png">

## Contact Me

Please do not hesitate to contact me for a live demo. I am more than happy to personally live demo to you. The source code for this project is available upon request. If you're interested in gaining access or have any questions, please contact me using the information provided below:

- Email: danjie.tang@outlook.com
- LinkedIn: [Danjie Tang](https://www.linkedin.com/in/danjie-tang/)

## Features that I am extra proud of:
### Progressive Disclosure
Displaying all the information contained in the map simultaneously can overwhelm the user with unnecessary details and result in long refreshing time. Therefore, it is necessary to optimize the amount of information presented. Inspired by Google Map, our team came up with a solution that prioritizes the most interesting points to tourism. As the user zooms in, less significant points will gradually appear(Figure 4). 

Zoomed Out (Freeways)             |  Zoomed In A Little (Big roads)
:-------------------------:|:-------------------------:
<img width="500" alt="Zoomed Out" src="https://user-images.githubusercontent.com/37476565/232181805-4c7d2d42-4db8-4a6d-bbcd-7db1040bb67e.png">  |  <img width="500" alt="Zoomed In A Little" src="https://user-images.githubusercontent.com/37476565/232181912-4cfdb08d-56ac-4959-8a0a-45235e64d2a9.png">
Zoomed In (Small Roads)             |  Detail View (Building and Restaurants)
<img width="500" alt="Screenshot 2023-04-14 at 11 56 23 PM" src="https://user-images.githubusercontent.com/37476565/232181936-a5d3e0cf-62d8-43f8-a8e4-46d5f3c31b5c.png">|<img width="476" alt="Screenshot 2023-04-15 at 12 05 57 AM" src="https://user-images.githubusercontent.com/37476565/232182075-8c35a1d3-840b-4bf1-9735-9dd3342afc86.png">

A* algorithm for path finding | Live Weather
:-------------------------:|:-------------------------:
<img width="500" alt="Direction" src="https://user-images.githubusercontent.com/37476565/232181232-0c3ca9b7-0e77-4911-83b1-656570b86e97.png"> | <img width="500" alt="Live Weather" src="https://user-images.githubusercontent.com/37476565/232181348-12a2207d-386f-4096-ba52-1316a7560e7e.png">

## No hard coding
This map supports 19 cities around the world, nothing is hardcoded! 
Beijing | Hamilton
:-------------------------:|:-------------------------:
<img width="1080" alt="Screenshot 2023-04-15 at 12 13 04 AM" src="https://user-images.githubusercontent.com/37476565/232182324-56fb4dbc-4db7-4349-b8ce-12413b12dcf4.png"> | <img width="1078" alt="Screenshot 2023-04-15 at 12 14 07 AM" src="https://user-images.githubusercontent.com/37476565/232182352-93dad895-3b36-434d-b44f-4e1f0b5cab25.png">
Singapore | New York
<img width="1081" alt="Screenshot 2023-04-15 at 12 15 01 AM" src="https://user-images.githubusercontent.com/37476565/232182358-22b14a88-ebf0-400b-89d4-11bc6d57322e.png"> | <img width="1080" alt="Screenshot 2023-04-15 at 12 16 37 AM" src="https://user-images.githubusercontent.com/37476565/232182399-8e6a678b-f065-4459-a5dd-dad2df33a6dc.png">
