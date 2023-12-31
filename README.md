# Unreal Engine 5 C++ Developer: Learn C++ & Make Video Games
This "critically acclaimed" and "insanely successful" Unreal Engine course was created in collaboration with Epic Games.

Link to the course: https://www.udemy.com/share/101XRs3@SPstzJtaJeN6LgwEAwdieiHCA0oAB7HnJ11OfC7fRaIZ7wbeBEUbHMWBFYomEVWlvA==/

# Game 1 (Warehouse Wreckage)
![image](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/1769e4e5-5158-41f2-b774-1e1160ec6469)

_A simple game in which we can shoot projectiles and destroy pyramids from barrels that have physics._

**Description of Implementation:**
1. Simple control Pawn (WASD);
2. Shooting projectiles (Space);
3. The number of projectiles (if the number is less than the maximum number, then you cannot shoot);
4. Simple level (Small room with barrels and rack);
5. Barrels and racks have physics.
6. ...

Link to the game: https://drive.google.com/drive/folders/1nAt75ZGduW0oRxra1zzBRFHT-gjMqymT?usp=sharing

# Game 2 (Obstacle Assault)
![1](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/e5c61ebd-5e39-48a4-97f6-c2f38db9651c)

A simple platformer with obstacles.

**Description of Implementation:**
1. Simple control Сharacter(WASD, Space), with animation;
2. Сorrect physics;
3. Different types of obstacles:  
    a. Moving platform(It can go up/down or move right/left);  
    b. A platform that rotates (it rotates around its axis), there are two types of platform and wall;  
4.  Simple level;
5.  Final prize.
6. ...

Link to the game: https://drive.google.com/drive/folders/1HhX0zoqq1nmFf_XwltvklmLjez0b8fhB?usp=sharing

# Game 3 (Crypt Raider)
![1111](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/dcfb8030-d79f-464b-99f1-70f8948e9248)

Here's a straightforward puzzle about dungeons, featuring secret rooms and cunning mechanisms that won't allow you to acquire the golden statuette so easily.

**Description of Implementation:**
1. Simple control Pawn (WASD, Space);  
2. Light(Lumen & Light Bleed);  
3. Implemented Grabber class (it can pick up some objects with certain corresponding tags);  
4. Implemented move walls:  
       a. The first wall opens if you place a statuette next to it (the trigger that opens a secret passage works);  
       b. The second wall closes when the statuette is taken from the stand in the dungeon, and opens when the statuette (or jug) is returned to its place;  
6. Simple Level;  
8. ...

Link to the game: https://drive.google.com/drive/folders/1wCfapl1J4TgRI46N-rLwpN-gczNitu1N?usp=sharing

# Game 4 (Toon Tanks)
![3 1](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/81b427dc-5af7-458a-9718-b247f6289249)
![3 2](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/0ba03d52-f285-49aa-9607-e226c0ac5b87)

A simple game in which you drive a tank and have to destroy all the turrets that shoot at your tank.

**Description of Implementation:**
1. Simple control Pawn (WA - move forward/backward SD - rotate a Pawn with a camera right/left);
2. Enemy (Turrets that fire in the player's direction every two seconds if the player is in line of sight)
3. Simple Shooting(Spawn a projectile and give it speed in the direction of the shot);
4. Projectile has a particle system (Trail and Destroy systems);
5. Sound (if we hit a projectile, which object is the projectile destroyed, and the corresponding sound is played [the sound of destruction or the sound of a simple hit]);  
6. Shaker Camera (the camera shakes when the projectile is destroyed [if the Base Pawn is also destroyed, then stronger]);
7. Simple level;  
8. Simple Lose/Win condition;  
9. ...

Link to the game: https://drive.google.com/drive/folders/1-VrOQEwj_S8R4w5vmgNOGy3pLtaCdPOc?usp=sharing

# Game 5 (Simple Shooter)
![game 5](https://github.com/Nazar-1k/Unreal_Engine_5_Curs-1/assets/82716260/51cfec85-9f49-485c-a627-39b7e0df8ca6)

A simple shooter in which you need to kill all the bots that shoot at you.

**Description of Implementation:**
1. Simple control Сharacter(WASD, Space);
2. Animation (Used Animation Blueprint, Blend Spaces, and Animation State Machines);
3. AI Enemy:  
    a. If the Player is in the field of view of the enemy, AI will start moving after you (If you disappear from the field of view, AI move to the place where the player was last seen, if the player is not there, return to the starting point);  
    b. AI always looks in the character's direction, given his position;  
    c. Shooting (If AI reaches the set distance to the character, AI starts shooting at him)
4. Gun Actor;    
5. Shooting (The Trace line will spawn);
6. Particle Systems (Impact Effects and Shooting Effects);  
7. Sound (Impact Sound and Shooting Sound); 
8. HUD (Simple Health Progres Bar, and Crosshair);  
9. Simple level;
10. Simple Lose/Win condition;
11. ...
    
Link to the game: https://drive.google.com/drive/folders/1XsAMs0gTONNB7Hd11U_9jOkXk4_sT4sI?usp=sharing
