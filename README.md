# CamelRace
A typical camel race in a local fair in a Spanish town
The rules are simple:
 - Camels run straight forward.
 - Each camel runs on his lane.
 - The winner is the first camel reaching the finish line.
 - each camel will move by the effect of the player pushing keys. Every time T (time of round), 
   the player will be requested to imput a set of three random letters.
   These letters must be inputed in less than time T'. For instance, given T' = 2,
   if the player is requested to input AXZ, and he does in less than a second, the camel will move X,
   if he does in less than 2, will move X/2, if he does in more than 2 seconds, the camel won't move. (T, T' and X are configurable).
 - The number of lanes, and thus, camels (one on each lane), will be configurable.
 - The terrain can be of three different types, the same for all lanes: Sand, Grass or Mud.
 - There are three types of camels: Bactrian Camel (never domesticated, it's big and strong, slower to move). Domestic Camel(strong and firm, good balance between speed and strength), Dromedary (the smallest, weakest and fastest)
 - Every camel has different abilities explained at the bottom.
 - The game won't be multiplayer. There is only one camel controlled by the player, while the rest are controlled by the CPU. 
ABILITIES:
 - Every camel has three attributes: 
    - Turbo Boost (depending on the terrain, and for a short period, a camel can move faster).
    - Weapon
    - Strenght
 - The Turbo Boost will be activated if the requested input contains the letters I or U.
 - The Weapon can be activated if the player strokes both the input and the reversed input within time T'.
 - Bactrian Camels: These camels feel more comfortable in Mud.
    - Turbo Boost: When activated, the camel will move a 15% faster for that round. A 30% faster if the terrain is Mud
    - Weapon: The Bactrian camel can perform a powerful kick backwards, making its immediate chaser to go backwards X steps.
    - Strength: When hit by other camel's weapons, it will reduce its effect by 20%
 - Domestic Camels: These feel more comfortable in grass.
    - Turbo Boost: when activated, the camel will move a 20% faster for that round. A 30% faster if the terrain is Grass.
    - Weapon: The Domestic Camel can perform an anoying sound, affecting the immediate rivals (the immediate forward and the immediate behind), causing them to reduce their speed by 50% in their next round.
    - Strenght: When hit by other camel's weapons, it will reduce its effect by 10%
 - Dromedary: These camels like the dry desert sand.
    - Turbo Boost: when activated, the camel will move a 25% faster for that round. A 35% faster if the terrain is Sand.
    - Weapon: The Dromedary can throw a powerfull gob of spit to the immediate camel forward. That camel will not move forward during the next round.
    - Strenght: This camel cannot reduce the effect of weapons on him.
