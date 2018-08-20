# Asteroids-Game

The features in this Asteroids Game:

Control Of the Game:
a). press "WASD" keys to move and diagonal moves
b). press "→←↑↓" keys to fire and diagonal firing

Team of FRIEND:
Falcon: use "WASD" to move: left(A), right(D), up(W), down(S);
        can increase lives with eating a blue FLOATER (NewShipFloater);
        the remaining time(Meter) of a NewShipFloater shown on the left upper screen with blue color;

Team of DEBRIS:
Debris(Gray): if Foe killed, gray Debris.

Team of FLOATER:
NewShipFloater(Blue): get a new live of Falcon
Goodie(Yellow): get fire power up(expires in 200 ticks). Fire changes from Bullet to Cruise and Cruise will reflect will it .                 touches the edges of the screen
Goodie(Green): get a shield(will expires in 100 ticks).
Bomb(Red): Bomb when falcon collides with it, all asteroid will be killed

Two situation for generating a floater:
a). When a big asteroid is killed, there is 50% chance to get a new floater
b). During some time interval, a new floater will randomly put 

Score and level:
Score: the current score and level will be shown on the left-top corner.

Level-up rule: Level will add one every time user earns 10000 points.
