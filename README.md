# Spotify Ad Removal for MacOS

I can't afford premium, so I decided to learn some basic Shell and make an app that mutes your sound when an ad plays. 

## How to Install
In terminal, navigate to the the directory where you want this folder stored -- PATH is the placeholder here. Then execute the following line: 

```bash
$ mkdir -p ~/PATH/MuteAdsSpotify && curl https://raw.githubusercontent.com/andr3wV/MuteAdsSpotify/main/index.sh > ~/PATH/MuteAdsSpotify/index.sh
# Replace PATH with desired path directory
```

This makes a directory containing the .sh file. Now you are all set! 

Run the following command anytime you want to mute spotify ads: 

```bash
sh ~/PATH/MuteAdsSpotfiy/index.sh
```

And remember to execute this command every time you exit the terminal window (via ^C or by closng the window). 
