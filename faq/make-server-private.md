---
description: How to make your Minecraft Server private on MCST
---

# Make Server Private

<details>

<summary>Method 1: Console (Recommended)</summary>

1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.

![](<../.gitbook/assets/image (27).png>)\
\
3\) Go to the console tab.

![](<../.gitbook/assets/image (15).png>)\
\
3\) Run the command `whitelist on`

![](<../.gitbook/assets/image (23).png>)\
![](<../.gitbook/assets/image (4).png>)\
\
To add players to your server, use the command `whitelist add playername`

![](<../.gitbook/assets/image (6).png>)\
\
To remove players from your server, use the command `whitelist remove playername`

![](<../.gitbook/assets/image (35).png>)\
\
Note:\
Commands submitted in console do not need a `/` prior to the command.

</details>

<details>

<summary>Method 2: In-Game</summary>

1\) Join the server you want to edit, the IP can be found on the console page of your server.

![](<../.gitbook/assets/image (26).png>)\
\
2\) Run the command `/whitelist on`

![](<../.gitbook/assets/image (30).png>)\
\
To add players to your server, use the command `/whitelist add playername`

![](<../.gitbook/assets/image (29).png>)\
\
To remove players from your server, use the command `/whitelist remove playername`

![](<../.gitbook/assets/image (31).png>)\
\
Note:\
You must have permissions to run these commands in-game.\
To add these permissions, follow the steps above:\
\
1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.

![](<../.gitbook/assets/image (18).png>)\
\
3\) Go to the console tab.

![](<../.gitbook/assets/image (8).png>)\
\
4\) Run the command `op playername`

![](<../.gitbook/assets/image (37).png>)

</details>

<details>

<summary>Method 3: Files</summary>

1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.\
3\) Navigate to the files tab.\
4\) Navigate to the root directory.\
5\) Navigate to\
6\) Edit the line `white-list=false` to `white-list=true`\
7\) Edit the `whitelist.json` file with the players you want to allow on your server.\
\
Recommended:\
For non-technical users, please use the methods above.\
\
Note:\
The line you need to edit may not be as described above, although similar.

</details>

