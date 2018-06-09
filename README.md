## Project-DBC

User Tracking/Group Tracking/IP Tracking


This is just a pet project, i cannot release the code as its bad, its tied to my work, and its taken a back seat, but i will get to it, but it is useful for a quick analysis on a certain user activity inside the infra.

Basic break down:

User Tracking searches the samaccount you put in, and pulls everything it possibly can, which devices (phones, tablets etc using A-S, etc) VPN Access, what home directory they have/Drive, computer name and ip, what groups they are in, if owa/mapi/etc is enabled or not, bunch of login/account info, UTM events pulled from firewall(s)/sniffing, folder access.

Group tracking will pull all the info for that AD Group, members, member of, created etc, also directory permissions if any.

IP Tracking will search the firewall for that IP and fill in the boxes, you can thing 'track' but selecting a port or ports, actions, etc (some or all) and then show just that info. 


Empty screenshots but i swear it works :)

![image](https://i.imgur.com/h7ejYxM.jpg)
![image](https://i.imgur.com/24ffQxi.jpg)
![image](https://i.imgur.com/idywZDp.jpg)
