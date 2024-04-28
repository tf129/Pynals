# The PYnals 
## Flag capture with characters

## 🎯 Description
The Pynals is a game developed in Python with the library [PytactX by Jusdeliens](https://jusdeliens.com/).
> 2 teams are fighting against each other to stay in the flag zone without any ennemy in with them.
> For more informations, go to [J-31](https://jusdeliens.com/2024/04/22/j-31-avant-le-d-day/)
## 🎲 Rules
### Components of the arena

[Arena schema](https://github.com/tf129/Pynals/blob/4196207dc95d355bcbf3bbc981740ec98a375476/Ressources/Images/map%20avec%20zone.jpg)
_Map size: 30x30_
There is many elements in the map:
- 🔴: target area
- 🔵: spawn area
- 🟡: spawn area
- 🟩: jungle


### Players 
There are 3 different profiles.

|Statistics|Light|Medium|Heavy|
|-----|-----|-----|-----|
|Life points|30|60|100|
|Cooldown between 2 moves|100|250|500|
|Cooldown between 2 fires|200|400|800|
|Hit fire|15|25|30|




### How to play
Your agent and your team agents spawn in one of the two sides of the map. You choose one of the 3 available profiles and try to stay in the flag area.

### How to win
You must stay in the flag area for 10 seconds in order to won a round. The first team to reach 5 round wins win.

## 🎮 Use cases
### Player
- Can choose his name
- Can move in x or y in 1 move with agent.move(dX,dY)
- Can turn in four directions (N, S, W, E) with agent.lookAt(dir)
- Can reload with reload()
## ✅ Prerequisites
- Python 3.12 or higher
- An arena in Pytactx (Given by jusdeliens)
## ⚙️ Installation
Installation of necesary packages automatically occur when an agent is created
## 🧪 Tests
## 🛣️ Roadmap
## 🧑‍💻 Author
Pytactx by Julien Arné, Under CC BY-NC 4.0 licence 👉 https://creativecommons.org/licenses/by-nc/4.0/deed.en

Map designed by Mathys Tola, go check his other arts [@default_asr](https://www.instagram.com/default_asr/)

Inspirated by Swevvenn

Developped by :
- Maxaug61
- Malagagne
- Swevvenn

## ⚖️ License
