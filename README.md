# Strange Farm
Second try at Hammer Editor, don't expect much.

### ![[Demonstration & Installation]](https://youtube.com/) 
This custom map is designed for farming strange kill counts in TF2 effortlessly, safe to say it gets the job done.
Poorly optimized so your laptop from 2008 will crash upon entering the map but it's fine.
Probably the best farming map as of today, definitely faster than those community servers.

*Requirements:*
- **An alt, or a friend**
- **Time** (Hale's Own in about 30 minutes to an hour, depending on how much you crank host_timescale up.)
- **Map** found in the repository, also in releases.

Please do NOT try to edit this map, *I am super ass and you will cry as soon as you see it*.

## Explained, awfully.
No joke just watch the video, it'll explain everything 10x better

## Step 1: Download Map
- Download the map from the repo, or releases tab
- Once done, drag it into your maps folder (**C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\maps**)

## Step 2: Launch a map
- You can launch any map, it doesn't matter as you will need to change it.
- *To do it with* **friends (lol)** *, set* **"Server Type"** *to* **"Public (Unlisted)"**.
![createserver](https://github.com/user-attachments/assets/ca92e3c7-5214-468e-8409-6700a9fdc6e3)

- Once you load in, open the developer console and smash your keyboard so that it types the following: ```changelevel farm_strange_v2```.

![changelevel](https://github.com/user-attachments/assets/f9be285c-41c5-4429-a543-d5920f4cc453)

## Step 3: Let the patient in
- To see the IP the server's hosted on, type the following into the developer console: ```status```.
- You will see a bunch of numbers, but we primarily need the first IP address from the line it says **"udp/ip"**.
- When you have it, tell your friend to type ```connect <the ip you got>``` into the console.

![status](https://github.com/user-attachments/assets/f8df6124-ff0f-40d0-aed6-794aba66c8b5)

## Step 4 & 5: Profit
- Your patient should start downloading the map when they type the connect command into their console, wait until so.
- **You** go RED team, **Patient** goes BLU team.
- When everything is set up, paste the following into your console (trust):
```sv_cheats 1; tf_damage_multiplier_red 99999; tf_damage_multiplier_blue 99999; spec_freeze_time -1; mp_respawnwavetime -1; mp_disable_respawn_times 1; tf_playergib 2; mp_idledealmethod 0; mp_idlemmaxtime 999999999999999999; host_timescale 20; addcond 74; addcond 75; removecond 75; addcond 72 -1; addcond 113;```
- If you also want to set your view & position, do ```setpos 35.346981 1.046116 69.031319;setang 2.094400 -179.440```.

Enjoy! Contact me on Discord ```@swingstuh``` if you have any problems or questions.
Help provided via the YouTube video.
