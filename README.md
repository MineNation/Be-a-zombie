Be-a-zombie
===========

  ModPE.setItem(507,"blaze_rod",0,"Staff");  Item.addCraftRecipe(507, 1, 0, [ 280, 3, 0]);  function attackHook(attacker, victim)  {  if(Player.getCarriedItem(attacker) == 507)  {  Entity.setHealth(victim, Entity.getHealth(victim) - 9);  } 
