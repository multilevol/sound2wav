# sound2wav
Grab current playing sound stream and store it in wav file.

Configuration:

  1. With pulseaudio running, create a loopback device:
        OPTIONAL: pacmd load-module module-loopback latency_msec=5
  2. Set the default (fallback) to loopback to current output device in pavucontrol:
       
Then you can start the script, wait 5 seconds, and you should have an output.wav.
