# Micromondoteca: a collection of Microworlds

The Micromondoteca features two ready-to-use Microworlds:
- Empty Microworld: Contains all the supported blocks.
- Reaction Game Microworld: A fun reaction game that can be played with three embedded systems, each with a LED matrix. Two of these systems also need to have an FC-51 IR sensor.

## Setupping Snap!

Clone this repository and checkout to the "pellonara" branch.

Depending on your WLAN configuration you can download the [offline version](https://github.com/jmoenig/Snap/releases/latest) of Snap! to make things easier.

Open the desired Microworld inside Snap!.

Enable JavaScript Extensions by going to the Settings menu on the top left bar.

Go to the "Microworld" group of blocks and right-click on the "Start up Microworld" block. Click on edit. 

A new dialog should pop up where you can change the IP address the Microworld connects to. Change only the IP address part to the IP address of the message broker (leave the `:20000` part unchanged).

Ensure the device running Snap! is connected to the same WLAN as the message broker and the embedded systems.

Enjoy!
