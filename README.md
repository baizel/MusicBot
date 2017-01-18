# RhinoBot: The music bot for Discord.

MusicBot is a Discord music bot written in [Python](https://www.python.org "Python homepage"). It plays requested songs and if the queue becomes empty it will play through a list of existing songs.

### How do I set it up?

[CLICK HERE](https://github.com/SexualRhinoceros/MusicBot/wiki) to find the guide that suites your operating system.

### Commands

Commands are listed [here](https://github.com/SexualRhinoceros/MusicBot/wiki/Commands "Commands list").

### Configuration

The main configuration file is `config/options.ini`, but is not included.  Simply make a copy of `example_options.ini` and rename to `options.ini`.  See `example_options.ini` for more information on how to configure it.

[CLICK HERE](https://github.com/SexualRhinoceros/MusicBot/wiki/Configuration) for more details.

### Great, now how do I use it?
Download the bot, set the dependencies up, then run `runbot.bat`! (or `run.sh` on mac/linux)  Read the tutorial if you don't know what to do.

If you have any errors, read the FAQ. If that didn't help, you can ask for assistance on the discord help server. Is is recommended to take screenshots so the developers can see errors.

[Rhino Help Server](http://discord.me/rhinohelp "Discord link")

### FAQ

Some frequently asked questions are listed on the wiki [here](https://github.com/SexualRhinoceros/MusicBot/wiki/FAQ "Wiki").

# MusicBot-With-Spotify
This is an extension to the MusicBot made by SexualRhinoceros (https://github.com/Just-Some-Bots/MusicBot). That lets you add songs from a Spotify playlist given its URI
<h1> If you already Have a bot Installed You only need bot.py. See <a href="https://github.com/baizel/MusicBot-With-Spotify">Here</a></h1>

You will need to create a developer app on Spotify to add the Spotify feature to your Bot.</br>
To do this visit https://developer.spotify.com/my-applications/#!/ and follow instructions.</br>
Keep a not of your Application Client Id and Secret ID. </br>
More Details on creating the app can be found on https://spotipy.readthedocs.io/en/latest/#authorized-requests

<h2> How do I add Spotify To My Bot</h2> </br>
<ul>
<li><a href ="https://github.com/plamere/spotipy">Install Spotipy </a> either using pip install spotipy or as specified by Spotipy. </br> </li>
<li>Fill Credentials in bot.py</li>
<li>Add 'spotify' to permissions.ini file </li>
<li>Run your Bot to see if it works.<br>If it did you should get a URL in the shell whcich you should visit.<br>
It should re-direct you to a new link. Copy this link.<br>
Paste it into the shell (This is part of Spotipy so for any refrence visit https://spotipy.readthedocs.io/en/latest/#authorized-requests)
</li> 
<li> Thats It! It should work, Hopefuly.</li> 
</ul>
