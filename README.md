# SteamdeckVirtualSurround
Steamdeck Surround Surround
March 21, 2023

Disclaimer This could cause issues with your audio if not performed correctly. I am not responsible for any damages to your Steamdeck or any device that uses this method. I'm not credited as the writer of this code or the .wav file generated below, I've only made them easy to utilize by reducing steps. Links are provided to the sources below.

What does it do:
This modification will allow you to achieve 7.1 virtual surround sound via your headphones or earbuds on the Steamdeck. It is similar to Tempest 3d Audio created for the PS5, but without height channels. The standard surround signal is remapped to frequenies that are altered by the natural shape of your ear and may differ per person's ear. I have tested Fallout 4 using the Xbox wireless headset and had great results. Results may differ per game and I would reccomended using stereo for anything that doesn't support more tha 2.1. This should be particularily useful for FPS and racing games. I hope you enjoy surround on the go!

Instructions:
Download the pipewire folder and unzip it
Enable hidden files and folders
Insert folder titled "pipewire" into /home/deck/.config
Resart the Steamdeck
Turn on your headphones
Right click your sound icon to configure audio, choose "Virtual Surround Sink." You may need to select your headphones first.
Note that your system will default to virtual surround, so you need to change it if you reboot and wish to use another source.

To disable or remove:
To disable the effect choose your normal headset or speakers in pulse3d (Sound may stop whlie channnging settings).
If you want to remove the program entirely, delete the "pipewire" folder in /home/deck/.config (It's important not to mix this up with your systems pre-existing pipewire.config file)

Links and credits provided here:

Code - https://gitlab.freedesktop.org/pipewire/pipewire/-/blob/master/src/daemon/filter-chain/sink-virtual-surround-7.1-hesuvi.conf

Sound profiles- (OpenAL Soft MIT KEMAR) is used for this profile.
https://airtable.com/shruimhjdSakUPg2m/tbloLjoZKWJDnLtTc

Code was uploaded by Wim Taymans. I would like to give a special thanks to Zenith22 from their "Youtube" channel at https://www.youtube.com/watch?v=Dc4lSt_-_uw&list=TLPQMjAwMzIwMjMGmIZONNVcwg&index=13

#I have only taken care of the necessary modifications to use this HRIF for the Steamdeck. Links could be broken with future updates. I will be updating the file if that occurs.
