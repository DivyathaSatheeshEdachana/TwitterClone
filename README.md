# Project 4 Part1 - TwitterClone and client tester/simulator

## Team members
Kanika Sharma | UFID : 7119-1343 <br />
Divyatha Satheeshan Edachana | UFID : 0710-8354

## Instructions to run the program :
1. Unzip SharmaEdachana.zip						
2. Go to directory TwitterclonePart1 by using the command :
cd TwitterclonePart1
3. Ensure Client.fsx, Server.fsx, Simulator.fsx and Messages.fsx are included in the compile in .fsproj file						
4. Through the command line, run the program using the commands :		 <br />						
First run the server process using :  <br />
dotnet fsi --langversion:preview Server.fsx  <br />
After server has started running, run the simulation file using :  <br />
dotnet fsi --langversion:preview Simulator.fsx numClients maxfollowerCount maxtotaltweets  <br />

( Note : Provide values for all 3 parameters :
numClients - number of users the simulation will have
maxfollowerCount - maximum number of users a user can follow
maxtotaltweets - maximum number of tweets a user can tweet )
