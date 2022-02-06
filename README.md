command /Thor:
    permission: Deadly.sword
    trigger:
        give player 1 of unbreakable iron axe named "&f&lThor's Axe"


on right click:
    if player's held item is iron axe named "&f&lThor's Axe":
        strike lightning at targeted block
	
	
on drop:
if player's held item is iron axe named "&f&lThor's Axe"
cancel event
