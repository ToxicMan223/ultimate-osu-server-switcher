<img align="right" src="https://i.imgur.com/tB6lgG4.png">

# Ultimate Osu Server Switcher

The UltimateOsuServerSwitcher is a server switcher for osu, that allows to switch between osu!bancho and various private servers.

# How it works

The Program fetches all its informations from the data/data.json file, which means its fully expandable even without a software update.

Switching to a different server or even bancho itself is fairly simple. You just choose the server you want to connect to from a list and
click the «Connect» button.

# How to add add server

If you wish to add a server, please follow these steps:

1. Ask the server owner (if not you) if it's okay to add their server to our switcher.
2. Collect the following data:
- The server name
- The server's website url
- The server's ip-address
- The certificate
- The certificate thumbprint (can be grabbed with our thumbprint reader, see releases)
- The server icon (It should be sized 48x48 due to performance)
3. Create an issue with the label "server request" or create a pull request.
we would prefer if you would create an issue rather than creating a pull request.
This will take the work off your hands and help us make our structure work better.

# In-deep explination

The server you are currently playing on is estimated by the ip that is deposited in the hosts file.
Switching a server includes deinstalling all certificates, modfying the hosts file, followed by installing the corresponding certificate
(if you chose to play on a third-party server).

The certificates will be installed on the local machine, rather than just the local user to avoid a warning prompt the user
has to agree with. This improves the switching agility to garantue the best user experience.

# Current server list

> Currently the following servers are listed:
>
> - [osu!bancho](https://osu.ppy.sh)     ![osu!bancho-logo](https://i.imgur.com/2bRmgxz.png)
> - [Ripple](https://ripple.moe)         ![osu!bancho-logo](https://i.imgur.com/2bRmgxz.png)
> - [EZPPFarm](https://ez-pp.farm)
> - [osu!Ainu](https://ainu.pw)
> - [Kurikku](https://kurikku.pw)
> - [The Realm](https://theosurealm.tk)
> - [Akatsuki](https://akatsuki.pw)

# GUI

We have a light theme and I dark theme. You can toggle between them in the bottom right corner of the about tab.

![Light theme](https://i.imgur.com/iqvpEpHl.png)
![Dark theme](https://i.imgur.com/ItqHz4p.png)
