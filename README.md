# Shooting-Game-MLAgent
 
Simple Shooting Game example

MLAgents trained shooter who can detect the targets and shoot when the shot is available. 

5 Trainings/ Trained models
1. Stand and shoot (Target always in front) - Failed 50k steps - too less steps (small time for shooting was given, the env. reset very quickly)
2. Stand and shoot (Target always in front) - Shooter learns to shoot within the timeframe
3. Shooter- directional movement, Target random location - Fail - only 1 ray perception sensor
4. Shooter- directional movement, Target random location -  Good results - 7 forward ray perception sensors- sometimes got slow as couldnt detect the enemies behind
5. Shooter- rotation and movement, Target random location - fully trained - forward dense ray perception sensors, added rotation to agent, some ray perception sensors at the blind spot(back) as well.

Future work - Adding obstacles, Self play
