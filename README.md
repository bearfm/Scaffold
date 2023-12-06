[![Build Status](https://jenkins.bennydoesstuff.me/buildStatus/icon?job=Scaffold)](https://jenkins.bennydoesstuff.me/job/Scaffold)

# Scaffold
My fork of Scaffold ("World management plugin for build servers.").

This project is a fork of Warzone's Scaffold, which itself is a fork of Avicus Network's [Build Plugin](https://github.com/Avicus/Scaffold).

## Wack Features

Falling below y -70 will teleport you to y 0 and give you upwards momentum. It's in ScaffoldListener.java if you feel like removing it.

## Server Setup

1. Start with the latest stable [Paper (PaperSpigot)](https://papermc.io/ci/job/Paper/) build.

2. Compile the latest version of Scaffold with Maven (mvn package).

3. Start the server. The 3 most basic commands in the plugin are ``/create``, ``/worlds``, and ``/open``.

## Permissions
| Command       | Description   | Permission Node |
| ------------- | ------------- | ------------- |
| `/lock`  | Lock a world at this time.  | `scaffold.command.lock`  |
| `/archive -d`  | Archive a world (use -d to delete).  | `scaffold.command.archive`  |
| `/delete` | Delete a world. | `scaffold.command.delete` | 
| `/create [world name]`  | Create a new world.  | `scaffold.command.create`  |
| `/open [world name]`  | Open a world.  | `scaffold.command.open`  |
| `/close [world name]`  | Close a world.  | `scaffold.command.close`  |
| `/export [world name]`  | Export a world.  | `scaffold.command.export`  |
| `/import <.zip file link> <world name>`  | Import a world.  | `scaffold.command.import`  |
| `/worlds`  | Show all worlds.  | `scaffold.command.worlds`  |
