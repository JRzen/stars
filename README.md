# Stars!

DockerHub base for Stars! container (www.starsautohost.org)

Intent:
A docker image that enables simple play of the classic 4x game *Stars!*.  The game was last updated in ~1997, but remains a challenging and engaging strategy challenge.  The game play is turn based, and various factors are exceptionally well balanced.  Detailed discussions of the game's strategy can be found at Stars AutoHost, where there is still a small but active community of players.
The original authors have given the webmaster at SAH permission to issue game keys for a small donation to keep that site running.

This repo will contain things like the Stars! binary required, and possibly some WINE compatible tools from AutoHost, to provide a docker container that makes Stars! just slightly harder to play now than it used to be (no 64 bit capability).
It is based on a wine/X11/VNC/novnc container which exposes the X11 interface over http.
