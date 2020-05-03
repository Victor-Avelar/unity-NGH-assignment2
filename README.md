# unity-assignment2-NGH

https://victor-avelar.github.io/unity-assignment2-NGH/

Key-M toggles between mouse or keyboard control. Mouse mode follows the cursor, keyboard mode uses WSAD
Space Bar - spawns an egg. An egg is destroyed when
It reaches the bounds of the world
It collides with an enemy
It collides with a waypoint
There are six waypoint objects in the system, names A to F.
When a waypoint object collides with an egg, it loses 25% of its opacity. This can be implemented by decrease the alpha channel of the SpriteRenderer color by 0.25. On the forth collision with an egg, a waypoint object will disappear and re-position itself in a new point that is randomly located at + or - 15 units in both X and Y from the initial position of the waypoint.

H-key hides and shows waypoints
There are always 10 enemies in the world
Enemy is destroyed when if it comes in contact with the Hero or when hit with an egg
When an enemy is destroyed, a new one spawns
An enemy sequences through the waypoints either sequentially (from A to F then back to A again) or randomly (waypoint chosen randomly)
J-Key switches between sequential waypoints and random waypoints
When a waypoint is moved, the enemy should move towards the new position
The display must include the game information as in the example (mouse/keyboard state, number of enemies touched, number of eggs in the world, number of enemies destroyed, cooldown for the egg)
