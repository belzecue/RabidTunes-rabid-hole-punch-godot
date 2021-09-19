# Rabid Hole Punch Godot

Godot plugin that, alongside the Rabid Hole Punch Server, allows peer to peer communication via UDP Hole Punching between devices that are behind NAT

## Installation and configuration

Clone this repository and copy the addons folder into your Godot Project.

Go to Project -> Project Settings -> Plugins -> Enable RabidHolePuncher

The plugin will be always enabled as a singleton, but you have to configure it first to use it.

Inside Godot, open the RabidHolePuncher.tscn file which will be inside "addons/rabidholepuncher/".

Click the node RabidHolePuncher which will be the root of this scene and check the node variables "Relay Server Address" and "Relay server port" and replace those with your relay server address and port (remember you **have** to set up a public accessible machine with the [Rabid Hole Punch Server](https://gitlab.com/RabidTunes/rabid-hole-punch-server) running for this to work)

## Usage

You have [an example project here](https://gitlab.com/RabidTunes/rabid-hole-punch-example) if you prefer checking directly how it works.

The RabidHolePuncher singleton has a couple signals and methods to get you running.

### Signals

### Methods


