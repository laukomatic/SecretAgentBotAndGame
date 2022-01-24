# Secret Agent Bot And Game
I want to create a player for a game I played with my friends, that will be far better than I could ever be with my current brain power.
If you want to join just contact me, I'm new to github and don't know how to use it well.

## First, I will explain how the game works for anyone to join and help with the project.

 ![image](https://user-images.githubusercontent.com/58361436/150691400-48a26547-ddda-4fdc-a19d-1b92249e86e9.png)
![image](https://user-images.githubusercontent.com/58361436/150691491-a5379fa0-30e6-40df-97a0-c8f929e40895.png)
![image](https://user-images.githubusercontent.com/58361436/150691535-1598a859-0d53-4cea-a7e7-b7b071bfe580.png)
![image](https://user-images.githubusercontent.com/58361436/150691634-35f657fb-18ed-43af-99ce-138e15cc52a4.png)
![20220123_183826](https://user-images.githubusercontent.com/58361436/150692089-191c6d52-2ee1-4052-92aa-37be0aad502e.jpg)
The first four images represent the 4 possible moving options, and the fifth picture is the map. The names are in my primary language, they don't matter. You can move from one place to another if they are directly connected by a line.
There are n>2 number of players, but it's better that there are at least 4, from experience. One of those is a secret agent and others are the police. 
Firstly, police choose their places on the board, than the secret agent chooses his place. 
![image](https://user-images.githubusercontent.com/58361436/150844271-66eeed82-0338-4e75-948f-edc4818a6769.png)

As seen from the picture he tells on where he is after moving from the red spot. The police has limited number of moves:
  6 Planes and Ships/Boats
  7 Cars and Trains
At the beginning, while secret agent has unlimited everything, he just has to tell what he'll use, for the move.

Let's go through the example. Let's say that there are 5 players(4 Police + 1 agent)
Than:
  1. Police chooses their initial positions, for example they choose: Madrid, Moskow(moskva), Berlin and Belgrade(Beograd). 
  2. Secret Agent chooses his place, which will count as his first move, let's say he chooses Paris(Pariz).
  3. After that Agent is first one on the move. This will be the second move, after making it(let's say he goes to Lyon) he writes it down and says he moved by car. 
  4. When he moves it's police's turn, they all move let's say that they move like that: Madrid -> Bordeaux; by train(now he has 6 trains left), Moskow -> Warsaw; by plane(5 planes left), Berlin -> Leipzig;(he can use car or train, let's say he chooses car - 6 cars left), Belgrade(Beograd) -> Rome(Rim); by plane 5 left.
  5. (As you can see everyone is a separate entity - they have their own tokens which they can't share with other police officers, even if they don't have them anymore.
  6. It's again Agent's move, he knows new positions of Police and how much tokens they have. So, he considers his next move and so on, till 6.
  7. When he reaches move 6 he makes a move and waits for Police officers to move, after that he tells them where he is and makes a move(like he would be on step one, except that this would than be his location). 
  8. This than continues till they catch him or till move 24 when all police officers are unable to move. 
  9. The further Agent comes the better, if he comes till move 24 and survives it he WON. 
If I was unclear, please say it I'll fix the problem. 
As you can see it's highly strategical game, based on probabiliies, that is why I think it could be automated.
