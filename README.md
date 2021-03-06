# Swarm Attack

This simulation on swarm attack within 2 beehives, The queen is the most potent to damages, The Warrior has good attackability, The Worker is like a pawn. Bees move in the direction of their prey with random velocities. With each hit, the health of enemy deplets, denoted by their fading out from background. Whereas the attacker gains a hit, as shown in table. The simulation stays until a Queen Bee is alive, queen's death marks as loss of whole swarm. Some bees have randomly been chosen to defend their position and they are the ones who are stable at same place. The tables on the sides show live score of each swarm. Any bee with negative health, is known to be dead. The net time of engagement and falling of one of the troop is shown in the counter. One can random the start position of Bees, with the randomization button. The notifier at the bottom shows live attacks & what is the status of it. Bees should be safe from corners as it's vulnerable to bees coming from either directions (N-W & S-E)

## Team A : Lime | 1 Queen | 15 Warriors | 20 Workers
## Team B : Red | 1 Queen | 15 Warriors | 20 Workers
 
 | Role  | Damage   | Look | Health |
|-------|----------|------|-------|
| Queen | 1 |![](https://raw.githubusercontent.com/Grv-Singh/imgtec-fullstack-challenge/main/vectors/Queen_bee_A.png)| 50 |
| Warrior | 4-7 |![](https://raw.githubusercontent.com/Grv-Singh/imgtec-fullstack-challenge/main/vectors/Warrior_bee_A.png)| 10 |
| Worker | 2-4 |![](https://raw.githubusercontent.com/Grv-Singh/imgtec-fullstack-challenge/main/vectors/Worker_bee_A.png)| 5 |
 
 * Immobile bees can be counted as defendants of beehive.
*  With respective damage of each bite, the health depletes, denoted by being faded away from playground.
 * Some bees seem to rotate in circle due to <a href="https://en.wikipedia.org/wiki/Stroboscopic_effect#:~:text=The%20stroboscopic%20effect%20is%20a,of%20short%20or%20instantaneous%20samples." target="_blank">Stroboscopic effect</a>.

### Check complete logs of simulation :
Input `console.log(logs);` in browser console

## Sources
Sound : <a href="https://www.soundsnap.com/" target="_blank">Bees Sound - Soundsnap</a>

Libraries : <a href="https://www.pixijs.com/" target="_blank">Pixie</a>

## References
Theory :  <a href="https://www.mdbka.com/bee-information/#:~:text=The%20main%20difference%20is%20that,food%2C%20insects%2C%20or%20spiders.&text=The%20worker%20bees%20are%20female,do%20not%20have%20a%20sting." target="_blank">Bee Information</a>

Idea : <a href="https://www.youtube.com/watch?v=mDR0_yfKQa0" target="_blank">Video</a>

## Future Scope
* Keyboard controls.
* Responsive Design

 #### Note : Clear cache once in a while, Github CDN seems to deliver audio not all the time. Simulation requires one to be active on tab.
