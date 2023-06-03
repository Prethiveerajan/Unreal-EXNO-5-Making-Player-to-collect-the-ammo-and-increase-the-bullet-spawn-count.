# Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count.
## EXNO 5
Making Player to collect the ammo and increase the bullet spawn count.
## Aim:
To Make the  Player to collect the ammo and increase the bullet spawn count.

## Procedure:
### 1.	Create a Bullet Projectile:
•	Follow the steps provided earlier to create a bullet projectile Blueprint in the Content Browser.
•	Set up the static mesh component and any other necessary components to define the bullet's behavior and appearance.
###2.	Set up the Rifle Blueprint:
•	Open the Rifle Blueprint that is attached to the character.
•	Locate the event or input that triggers the firing action.
•	Create a custom event node for spawning the bullet projectile.
•	Use the "Spawn Actor from Class" node to spawn the Bullet Projectile Blueprint.
•	Connect the execution line from the event node to the Spawn Actor node.
### 3.	Configure the Spawn Actor node:
•	In the Spawn Actor node, select the Bullet Projectile Blueprint as the class to spawn.
•	Connect the execution line from the Spawn Actor node to any additional nodes or logic related to the firing action.
### 4.	Adjust the spawn location and rotation:
•	Add a "Get Socket Transform" node to retrieve the transform of the rifle socket where the bullet should spawn.
•	Select the appropriate socket in the character's skeletal mesh.
•	Connect the output of the Get Socket Transform node to the Spawn Transform input of the Spawn Actor node.
### 5.	Add the ammo collection animation and bullet spawn count increase:
•	Import or create an animation asset for collecting ammo.
•	Create a variable in the character's Blueprint to track the bullet spawn count.
•	Add logic to increase the bullet spawn count whenever ammo is collected.
•	Create a sequence of nodes that plays the ammo collection animation when triggered.
•	Use the bullet spawn count variable to determine the appropriate number of bullets to spawn during the animation.
### 6.	Test the bullet spawning and ammo collection:
•	Compile and save the Rifle Blueprint and Bullet Projectile Blueprint.
•	Play the game to test the character's firing action and ammo collection.
•	Verify that the bullet projectile spawns from the rifle socket with the desired behavior.
•	Ensure that the ammo collection animation plays correctly and increases the bullet spawn count accordingly.

## OUTPUT:
## Relod Actor:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count./assets/94233064/9238da2d-a287-4333-9f31-1c3d075db3d0)

  




## Reload Actor Event Graph:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count./assets/94233064/a5657f1d-724f-4bb0-8078-b5b76392ea0d)

  
## Bullet Spawn And count:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count./assets/94233064/1781ec44-005a-4150-9c34-1e57bb882abe)

  
## Player Before Collecting Bullets:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count./assets/94233064/0550b8b1-9a5c-4cb6-a1db-8f091a66783a)

 
## Player After Collecting Bullets:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-5-Making-Player-to-collect-the-ammo-and-increase-the-bullet-spawn-count./assets/94233064/d6c5cfe4-18cb-47bc-8718-08ebdab03450)

 
 Prethi>ee


## Result:
Thus we successfully created a Player to collect the ammo and increase the bullet spawn count


