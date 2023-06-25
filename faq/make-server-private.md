---
description: How to make your Minecraft Server private on MCST
---

# Make Server Private

**Method 2: Console (Recommended)**\
1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.

![](<../.gitbook/assets/image (25).png>)\
\
3\) Go to the console tab.

![](<../.gitbook/assets/image (13).png>)\
\
3\) Run the command `whitelist on`

![](<../.gitbook/assets/image (21).png>)\
![](<../.gitbook/assets/image (4).png>)\
\
To add players to your server, use the command `whitelist add playername`

![](<../.gitbook/assets/image (6).png>)\
\
To remove players from your server, use the command `whitelist remove playername`

![](<../.gitbook/assets/image (32).png>)\
\
Note:\
Commands submitted in console do not need a `/` prior to the command.

\
\
**Method 3: In-Game**\
1\) Just the server you want to edit, the IP can be found on the console page of your server.

![](<../.gitbook/assets/image (24).png>)\
\
2\) Run the command `/whitelist on`

![](<../.gitbook/assets/image (27).png>)\
\
To add players to your server, use the command `/whitelist add playername`

![](<../.gitbook/assets/image (28).png>)\
\
To remove players from your server, use the command `/whitelist remove playername`

![](<../.gitbook/assets/image (30).png>)\
\
Note:\
You must have permissions to run these commands in-game.\
To add these permissions, follow the steps above:\
\
1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.

![](<../.gitbook/assets/image (16).png>)\
\
3\) Go to the console tab.

![](<../.gitbook/assets/image (8).png>)\
4\) Run the command `op playername`

![](<../.gitbook/assets/image (35).png>)

\
\
**Method 1: Files**\
1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.\
3\) Navigate to the files tab.\
4\) Navigate to the root directory.\
5\) Navigate to\
6\) Edit the line `white-list=false` to `white-list=true`\
7\) Edit the `whitelist.json` file with the players you want to allow on your server.\
\
Recommended:\
For non-technical users, please use the methods below.\
\
Note:\
The line you need to edit may not be as described above, although similar.
