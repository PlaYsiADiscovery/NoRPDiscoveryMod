NoRP Discovery Mod
=============
Tested Base Discovery Version: 4.95.0 Patch 9


Thanks to
-------

Rockstar for help testing.
The helpful people in the Freelancer Galactic Community discord.
All of the Discovery Developers over the years for the great mod we are tweaking.
All of the Discovery Developers who have helped me get stuff working.


What are we doing here?
-------
Mostly removing RP stuff from discovery when I believe or am convinced it will improve gameplay for a Non-RP Discovery server.


How to get it working
-------
Mods in the ServerSide folder can be safely done (according to our testing) on the server only.
Mods in the CliendSide folder will need to be done on both the server AND the client.

HostileMOD:
- Copy the 2 files into your DATA/MISSIONS directory. 
- --For me this was D:\Discovery Freelancer 4.91.0\DATA\MISSIONS because I installed the Discovery mod there.
- Rename the original files to "faction_prop.ini.orig" and "pilots_population.ini.orig"
- Rename the HostileMOD files to "faction_prop.ini" and "pilots_population.ini"

Server FLHook:
- Follow the instructions on the flhook github for that side of things https://github.com/brac3r/FLHook


Changelog
-------

v1.1
Here are my notes as I was going through the pilot file, you can glean the exact changes by using compare

*Gun Ace Changes*
Outcast more in line with corsair, they were... formidable

*Gun mismatches*
Fixed a bunch of "easy" pilots using "ace" gun ids and other similar problems

*Other*
Most evade/buzz toward and so on seemed to match pilots, left alone.

v1.0
Implemented what I call HostileMOD. A server side data files tweak that:
- Has enemy NPCs actually attack you, instead of waving at you for ease of RP reasons. The universe is a lot less tame now.
- Restored NPC scanning, ie: Police scanning you for that cardamine etc...