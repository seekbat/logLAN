# logLAN
A DNS based log-in system Computernetworks. I want to Use ist for LANpartys


This system contains a Bind9 configuration, a Website and a Shellscript.


## Bind
Bind has the functionality of creating multiple views. So I use one as a DNS-Blockhole which answers always with the same IP. The Second View always Forwards the Request to a Predefinied Server.

## Shellscipt
The shellscript is used to handle the bind-configuration to change an IP from the unauthenticated list to the authenticated list.

## Website
The website is the captiveportal for the user to authenticate.
