# 2D-Character-for-3D-World-Unreal-Engine-Blueprint

Walkthrought how to use and deploy on youtube:
https://youtu.be/suFrbG236Kg
______________


# Steps to Deploy

1) Download the folder ThirdPersonBP

2) Create new game project in Unreal Engine (3D character)

3) Put downloaded files in "MyProject\Content\ThirdPersonBP" folder

4) Add to project settings --> UI

4.1) Go to Project Settings --> Project Maps and Modes --> Game inscance Class --> Set it to "Main Instance)

4.2) Go to Project Settings --> Engine Input --> add if not exist:

4.2.a Jump - assign button space

4.2.b Sprint - assign button shift

4.2.c Rotate90L - assign button "Q"

4.2.d Rotate90R - assign button "E"

4.3) Go to Project Settings --> Engine Collision --> add trace channels:

4.3.a LedgeTrace - Ignore
4.3.b BattleTrace - overlap


# References. Thanks to people that publish tutorials:
1) Climbing system based on Marcos Medel tutorial --> UE4 Climb System - Tutorial - Part 1 - Grab & Climb-Up https://www.youtube.com/watch?v=BKiSTM-G9pQ
2) Walking system based on Two Star Games tutorial that disapeared, but check him out -  https://www.youtube.com/c/TwoStarGames/videos
3) Switching between the AI and player controller is based on  Kyle Dail - UE4 AI Control, Possession and Pawn Switching https://www.youtube.com/watch?v=mNtm2fAHObg
4) NDI handling is based on  Humble Ninja https://www.youtube.com/watch?v=Vwr1MMVBqo0&t=3542s
5) Helped me with debugging the light in Unreal Engine - Brukel Game - Unreal Engine 4 Tutorial | Fixing inaccurate shadows and light bleed https://www.youtube.com/watch?v=7SDNRWYGo8k&t=275s
