---
description: How to fix connection refused errors.
---

# Connection Refused

This applies if you are attempting to connect to your server, but are receiving no error message(s) in console.\
\
1\) Verify you are using the correct IP, which can be found on the console page of your server.\
2\) If you're using a proxy, verify you are using the IP of your proxy server.\
\
If those steps don't work, follow the steps below.\
\
1\) Navigate to your server panel.\
2\) Navigate to the server you want to edit.\
3\) Go to the files tab.\
4\) Navigate to the root directory.\
5\) Navigate to `server.properties`\
6\) Check the line `server-port`, if this is not the same as the port found on the console page, follow step 7. If it is the same, create a ticket on our [Discord Server](https://discord.gg/dzAxSz5C4x)\
7\) Change the port from `25565` to the port found on your console page.
