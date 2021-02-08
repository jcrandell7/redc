# redc
used for batching the process of speeding up a recording (phone calls) and normalizing pitch so that it doesn't take as long to listen to the recordings.

first you need to install SoX and mp3 libraries. In your terminal run:
sudo apt-get install sox
sudo apt-get install libsox-fmt-mp3

Put the script "redc" somewhere in your $PATH and you're ready to use it.

In your terminal type in:

redc <absolute path to the directory you want to work in>
  
  example:
  
  redc /home/jordan/Desktop/mp3files/
  
  hit enter and it will go through all of the audio files and speed them up, normalize the pitch, max out the sampling rate and add a filter to avoid clipping.

