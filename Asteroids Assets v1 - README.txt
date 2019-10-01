transparency.png
---resource file. This is the raw sprite sheet with transparency. Use this as your asset. 

Asteroids Assets key - 6x6 tiles - 64x64 px each.png
---notes for the sprites and animation sets
---For the ship thruster, row 1 - Column 2,3,4,5,6 is the loop. You can also just animate it 2->3->4->3->2. 5 and 6 weren't really needed as they duplicate 2 and 3. I found giving the ship thruster frames 10ms each seemed good.
---For the missile thruster (if you want to try to add some missile tracking / manuvering logic, or just use them as straight-line rockets), just alternate between the two. I found giving the missile thruster frames 50ms each seemed good.


Asteroids Assets v1 - JSON Tilemap.json
Asteroids Assets v1 - TXT Tilemap.txt
Asteroids Assets v1 - XML Tilemap.xml
---tilemaps that my pixel editing app generates. Not sure if Godot can use these, but figured I'd generate them just to see if they're usefull :)

