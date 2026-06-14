# Roblox-Game-Analytics
Free commisioned work, a Roblox analytics dashboard designed to help game owners or players manage their creations and track game performance, statistics, and player activity.

# GETTING STARTED 
First, download / make copy of google sheet. 
https://docs.google.com/spreadsheets/d/1DYHxFtHtylXnY8FGte1zVl9sqCqxy0enPVKJUY7T6P0/edit?usp=sharing

Once you have your copy, click Extensions, and App Scripts. It should open another window where you will see the code of the project.
<img width="705" height="246" alt="image" src="https://github.com/user-attachments/assets/246f6fd2-fe06-4d33-81fa-d13a8e83471a" />


Inside the code, you can easily find what to edit and change, using CTRL + F on your keyboard and type "ROBLOX_GAME_ID". Change to roblox game ID;
var universeId = 'ROBLOX_GAME_ID'; 

<img width="412" height="85" alt="image" src="https://github.com/user-attachments/assets/ea0ac047-8554-4a1b-9442-0aa13f6d0997" />


Searching again, CTRL + F, type "GROUPID_HERE", you should see 

<img width="511" height="103" alt="image" src="https://github.com/user-attachments/assets/ffd5f67a-a568-48d6-817c-5a8b3b1e0015" />


Change "GROUPID_HERE" to Roblox Group ID number. Next, assign it a column, inside the "departments" tab on the sheet, for this example next column would be B.

Lastly, At the top, at the taskbar where you see "Run", "Debug" you should see function names with dropdown box, in the image below select each one and press "Run" button to create the triggers to automationly run for you.
It will as you to if its allowed to run on your account, accept.
<img width="563" height="296" alt="image" src="https://github.com/user-attachments/assets/f57aed35-740c-4504-bc75-c9f3a789d674" />

After that you are all done, now everyday your google sheet will automantly pull roblox api to get current player count of your game, every 5 minutes it will pull player count, and everyday google sheet will pull your group members and log it into a graph for yourself. After awhile you will notice data trends and see it slowly fill up like so;

<img width="1863" height="806" alt="image" src="https://github.com/user-attachments/assets/ab3c5da5-3a0d-40c3-979e-253030054924" />
