# nextcloud_server
Sick and tired of google

Summary:

I reached my storage limit for my google drive prompting them to ask me to pay $2 a month to expand my storage capabilities. I got mad and decided to instead spend $60 and a dozen hours figuring out how to self host my own "Google Drive." NextCloud seemed to be the option that most closely matched what I needed (primarily photo storage capabilities). Other options that didn't make the final cut were OwnCloud and LibrePhotos. Setting up NextCloud was easy enough. But learning how to harden a server and reduce the . I'm not going to share the exact details of everything that I did, but here's a rough synopsis.

Basic Outline:

1. Bought computer from surplus store
2. Installed Ubuntu Server on it
3. Found and followed documentation on hardening ubuntu server
  a) Noted changes that needed to be made upon installation of ubuntu server next time.
4. Installed NextCloud
5. Wiped the computer and repeated steps 1 to 3 with modifications suggested from previous attempt
6. Installed Greenbone Vulnerability Software on another computer
7. Used it to attack the server
8. Learned I needed to configure things differently... again :(
9. Wiped computer AGAIN and made necessary changes
10. Ran Vulnerability assessment. Much better score this time.
11. Installed NextCloud
12. Somewhere in here I utilized a free DNS to point a url to my ip address
13. Also forwarded some ports...
14. Ran Greenbone assessment again after setting up server. Good score still.
15. Currently waiting to see if I get hacked :)

Links:



Results:

Seems to be working fine. The internet provider seems to think that there is malicious activity, but after looking through a couple different logs and running anti-malware screening every now and again, it seems that the server is holding its own. Uploads photos just fine and can view from anywhere I have internet.

For next time?:

