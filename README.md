# HalloweenTown
Ethernet based server, client and device software for a haunted house

Nothing works yet. The server will work on a host machine connected to an ethernet network. Once it is up and running, it will broadcast itself to all active clients and devices.

A client runs the HalloweenTown_Client code - it's type determined by a plug in or something. These would be computers where users input control info to be sent to a device.

A device runs the HalloweenTown_Device code - it listens for a HalloweenTown server, connects to it, identifies itself. The server will then allow clients to identify and connect to the device. All devices should have a unique ID (given to it by the server if it doesn't have one?) so pairings can be assigned and saved.

Planned devices are:

Ultrasonic speaker - (with x/y axis adjustment?) so you can stream audio from a client microphone and directionally whisper in people's ears.

Magic mirror - captures face orientation and markings as well as audio, sends that to a device that renders an image and plays the audio. Should be a screen behind a one-way mirror. Device should stream audio and video back to the client.

Actuators - client side connects to a device. Device tells it the appropriate range of motions (tilt a dummy head, push a piston out, rumble a spooky grate, etc...). Device responds to client side command.

Lighting - simple light controller i guess?

Atmospherics - client side that manages multiples devices - smoke machines, strobes, etc.
