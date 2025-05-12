### What is it?
Reticulum Network Stack is just as it says on the tin. Where the other players in the open source LoRa scene are mainly chat tools, Reticulum is a network stack with a chat protocol (as well as other protocols). 
### Why create another mesh? 
Reticulum was created with a broader scope than meshtastic or meshcore. Currently you can create a micron page and serve up something between a BBS page and a webpage, send images and make voice calls over low bandwidth LoRa Connections.
### What is the reticulum topology like?
It can be however you want it. The easiest way to implement an RF only reticulum network between homes and regionally is to setup a network connected raspi with an rnode up high to connect to the city-wide mesh. That single transport node will share the mesh over your home network without having to carry around mesh nodes everywhere you go.
### HF connections
We have tested an HF connection between Chicago and mid-Michigan. It's not always up, but can be if we get at least another person onboard. This connection is much slower, somewhere around 1200 baud. This is enough for messaging, but not the greatest for browsing nomadnet. We are currently testing on the (unpoliced) 6.78mhz HF ISM band which does not require a licence, but is supposed to be run with lower power.
