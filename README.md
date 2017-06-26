# MusicBot-With-Spotify
This is an extension to the MusicBot made by SexualRhinoceros (https://github.com/Just-Some-Bots/MusicBot). That lets you add songs from a Spotify playlist given its URI

<h2>Current Features </h2>
<ul>
<li> Play any playlist from Spotify using its URI </li>
<li> Start a radio with a given artist (Pretty much like Spotify radio)</li>
<li> Maybe more?  </li>
</ul>

<h1> Requirements </h1>
<ul> 
<li> Spotipy </li>
<li> MusicBot Installed </li>
<li> python 3.5.1+ </li>
<li> Spotify Account </li>
</ul>
<h2> How do I add Spotify To My Bot</h2> </br>
<h3> Notes </h3>
<p>You will need to create a developer app on Spotify to add the Spotify feature to your Bot.<br>
To do this visit https://developer.spotify.com/my-applications/#!/ and follow instructions.<br>
Keep a note of your Application Client Id and Secret ID. <br>
More Details on creating the app can be found on https://spotipy.readthedocs.io/en/latest/#authorized-requests </p>
<ul>
<li><a href ="https://github.com/plamere/spotipy">Install Spotipy </a> either using pip install spotipy or as specified by Spotipy. </br> </li>
<li>Fill in Credentials in bot.py (Its at the bottom of the page) and then replace it. </li>
<li>Add 'spotify' to permissions.ini file (As seen on example_permissions.ini) </li>
<li>Run your Bot to see if it works.<br>If it did you should get a URL in the shell whcich you should visit.<br>
It should re-direct you to a new link. Copy this link.<br>
Paste it into the shell (This is part of Spotipy so for any refrence visit https://spotipy.readthedocs.io/en/latest/#authorized-requests)
</li> 
<li> Thats It! It should work, Hopefuly.</li> 
</ul>

<h1> Usage </h1>
In discord use {pre-fix}spotify spotify:Uri:Format:like:This <br>
This works by getting a spotify URI then using Spotify API to get all the tracks inside the playlist. Then playing them using the built-in play method.

<h1> Disclaimer </h1>
This DOES NOT stream from Spotify. Only gets Track Names and then uses youtube to get the music


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

