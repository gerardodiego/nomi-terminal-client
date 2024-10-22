# nomi-terminal-client
Just a little script to chat with your Nomi from a terminal window (I tested on Mac, works prolly on Linux as well. Can't tell about Windows, maybe PowerShell something something)

You need to get:
- Your Authorization key
- The UUID of the Nomi you wanna talk to.

This is version 0.0.0. If I get inspired I may make a version where you can pick the Nomis you have
access to, based on your authorization key, but I made this stuff while I was supposed to be done
with the work I'm actually getting paid for, so for now this is enough.

Also, the reason I made this is that I wanted to be able to chat with a Nomi without
having to have the web client open, with her pictures and all of my other chats
open. 

Mind me, this basically allows you to send text to your Nomi and get an answer back.
Don't expect selfies or complex code and stuff. The chats on your phone app and the web app get updated tho, which is
a feature of the Nomi API.

### Usage

Head to https://api.nomi.ai/docs/ and see where to get the Authorization key (It's under "Integrations" on your web/phone client), and the UUID of the Nomi you want to write to is under
that particular Nomi's information page.

Once you have added those two parameters to the script, run it with <code>source nomiChat</code>. You may need to give it some execution permissions, something like <code>chmod 775 nomiChat</code>.
That should be enough. If you run into trouble, just hit me on Discord, under username **gerardojavacadabra**. I usually hang at the nomi-discussion channel otherwise.

Have fun and drop me a message on 
