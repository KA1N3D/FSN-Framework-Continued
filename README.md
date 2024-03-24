# Fusion Roleplay Framework (Otherwise known as FSN)

Fusion Framework is a newly launched framework on the FiveM platform, created specifically for British Roleplay communities. The aim of FSN is to provide advanced features that match those offered by paid frameworks, but at no cost at all. The framework includes essential tools for running a high-quality FiveM server, along with many other features that enhance the overall experience. The framework was initially developed by JamesSc0tt [https://github.com/JamesSc0tt/FiveM-FSN-Framework] and has now been passed on to Fusion Dev Studios to continue its development. The ultimate goal is to provide a framework that contains every script required to run a high-quality modern-day roleplay community for no cost.

#### Support / Issues / Feature Requests
This framework has not been touched for the past 2 years, there are currently many bugs which will be addressed in the weeks to come, a lot of features may also be outdated and we already have plenty of new features actively being developed! If you have any issues, questions or wish to participate with the continued development of FSN Framework then please join our Discord Server: https://discord.gg/2ZxQDJzC54

#### Requirements
- x86-64 system running Linux or Windows (7/2008 R2+), decent upstream connection.
- FiveM Reborn Server
- Local/Remote MySQL database server
- At **LEAST** 4GB disk space (including room for future updates) 
- MySQL Server

## Installation
Install the required below resources. Set up mysql-async, and add this to your server.cfg:
```
ensure mysql-async
add_ace resource.fsn_main command.start allow
ensure fsn_main

[ENSURE ALL NON FSN_* RESOURCES HERE]
```

The framework is designed to create all the tables for you in your DB upon successful connection to your database. If your database is not connected or you are not running mysql-async or have no clue how to do that then search it. We wont provide support on correctly and succesfully connecting to your database

#### Alongside the FSN [resources](https://github.com/jamessc0tt/FiveM-FSN-Framework/blob/master/fsn_main/resources.txt), the "framework" is built to work with the below publicly available resources.
- mysql-async (https://github.com/brouznouf/fivem-mysql-async)
- interactsound (https://github.com/plunkettscott/interact-sound)
- K9 (https://github.com/xander1998/k9)
- Luxart Vehicle Control (https://forum.cfx.re/t/release-luxart-vehicle-control/17304)
- mhacking (https://github.com/GHMatti/FiveM-Scripts/tree/master/mhacking)
- mythic notify (https://github.com/JayMontana36/mythic_notify)
- nativeui (https://github.com/FrazzIe/NativeUILua)
- tokovoip (https://github.com/Itokoyamato/TokoVOIP_TS3/releases)
- xgc tunerchip (https://github.com/VoXzE/xgc-tunerchip)

#### License
You are free to use/modify the "framework" in any way you see fit, remember to contribute any worthwile changes to the project with a merge request. Please do not distribute the project without my explicit permission. Do **NOT** remove the "FSN Framework v2.1.4 by JamesSc0tt & iTzCrutchie" on the character selection/creation screen.
