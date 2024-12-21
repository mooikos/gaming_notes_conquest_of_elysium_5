# units_base

generic_undead_traits
* immunity_charm
* immunity_sleep
* mindless
* never_heals
* 100 resistance_cold
* 100 resistance_poison
* undead (banishable / double damage_holy)

archer
catapult
crossbowman
heavy_infantry
spearman
swordsman

soulless_soldier (soulless / 5 iron)
* stats
  * 13 hp
  * 5 strength
  * 99 morale
  * 1 resist_magic
  * 1 armour
* skills
  * generic_undead_traits
  * amphibian
  * clumsy
  * 50 resistance_pierce
  * shield
  * slow
* attack
  * spear
    * 6 initiative
    * 1 range
    * 1-4+1 damage_piercing

armoured_soulless (soulless / 20 iron)
* stats
  * 15 hp
  * 5 strength
  * 99 morale
  * 1 resist_magic
  * 2 armour
* skills
  * generic_undead_traits
  * amphibian
  * clumsy
  * 50 resistance_pierce
  * shield
  * slow
* attack
  * broadsword
    * 4 initiative
    * 1 range
    * 1-6+1 damage_piercing

armoured_longdead (20 iron)
* stats
  * 5 hp
  * 4 strength
  * 99 morale
  * 1 resist_magic
  * 2 armour
* skills
  * generic_undead_traits
  * amphibian
  * 50 resistance_pierce
  * shield
* attack
  * broadsword
    * 4 initiative
    * 1 range
    * 1-6 damage_piercing

bane_fire_archer (10 hands_of_glory)
* stats
  * 3 hp
  * 4 strength
  * 99 morale
  * 1 resist_magic
  * 0 armour
* skills
  * generic_undead_traits
  * amphibian
  * 50 resistance_pierce
* attack
  * bane_fire_bow
    * 2 initiative
    * 5 range
    * 1-3 damage_piercing
    * 1-2 damage_magics
    * decay

bane_bones (10 iron / 5 hands_of_glory)
* stats
  * 5 hp
  * 4 strength
  * 99 morale
  * 1 resist_magic
  * 1 armour
* skills
  * generic_undead_traits
  * amphibian
  * 50 resistance_pierce
  * shield
* attack
  * bane_blade
    * 4 initiative
    * 1 range
    * 1-3 damage_slash
    * decay
