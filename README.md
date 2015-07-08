# map-generator
"Blind ant" random map generator

Written by Philip Yoo

The script used to generate the map uses randomness to "carve" out oceans. Originally, I wanted to create a cave generator using "blind ants" where a number of ants randomly wanders around carving out dirt to create a cave system. I still have remnants of the blind ants generator in the script in the comments. I then decided the random patterns look better as land and water so I shifted over to map generation. Here, I have three workers carving out oceans. Each add iterates over several thousand times where the workers blindly carve and move around. It also cleans up the map by removing blocks depending on the number of empty blocks around it. I found out that clean up factor 4 creates the best-looking maps, but anything above seems to create more detailed yet "dirtier" maps. I started this short project as a way to learn more Javascript and some HTML/CSS.