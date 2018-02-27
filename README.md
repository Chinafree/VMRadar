# PUBG-Radar

https://github.com/SamuelNZ/VMRadar/releases

![Imgur](https://i.imgur.com/tMjF1xw.png)

This version runs without the spoofing shit in a VM.

'Fixed' the item locations, still working on it.

### Key Kinds

You can't filter meds and level 3 gear

#### Item Filter:
>NUMPAD_0 -> Show / Hide Compass (Hidden By Default)

>NUMPAD_1 -> Filter Weapon

>NUMPAD_2 -> Filter Attachments

>NUMPAD_3 -> Filter Level 2

>NUMPAD_4 -> Filter Scopes

>NUMPAD_5 -> Filter Meds

>NUMPAD_6 -> Filter Ammo (Includes Grenades)

#### Zooms:
>NUMPAD_7 -> Scouting

![Imgur](https://i.imgur.com/laRIJq1.png)

>NUMPAD_8 -> Scout/Loot

![Imgur](https://i.imgur.com/sAXPkR2.png)

>NUMPAD_9 -> Looting

![Imgur](https://i.imgur.com/wnB3b7d.png)

### Online Mode:

`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar 192.168.1.70 PortFilter 192.168.1.67`

### Offline Mode:

You can replay a PCAP file in offline mode:

`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar 192.168.1.70 PortFilter 192.168.1.67 Offline`

## Build
Using [maven](https://maven.apache.org/) or [JetBrains](https://www.jetbrains.com/idea/)

## Run

Using a VM that supports OpenGL3.2 or on another machine, You shouldn't be using this on your gaming PC.

You need to install JRE8 not JRE9.



