---
type: pc
race: "Dragon (gem)"
class:
 - "Ancient Amethyst Dragon"
subClass:
 - "CR 23"
cover: "Ancient Amethyst Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/23
  - source/ftd
---
###### Ancient Amethyst Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Amethyst Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (gem) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 444 (24d20 + 192) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 27 | 26 | 19 | 23 |
| **Mod** | +8 | +2 | +8 | +8 | +4 | +6 |

**Speed:** 40 ft., fly 80 ft. ((hover)), swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 28
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +15, Wis +11, Cha +13
**Skills:** Arcana +22, Perception +18, Persuasion +13, Stealth +9
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened; prone

---

### Traits

**Amphibious.** The dragon can breathe both air and water.

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +15 to hit, reach 15 ft., one target. *Hit:* 19 (2d10 + 8) piercing damage plus 13 (3d8) force damage.

**Claw.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 15 (2d6 + 8) slashing damage.

**Singularity Breath (Recharge 5–6).** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 90-foot cone. Each creature in that area must make a DC 23 Strength saving throw. On a failed save, the creature takes 63 (14d8) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Explosive Crystal (Costs 3 Actions).** The dragon spits an amethyst that that explodes at a point it can see within 60 feet of it. Each creature within a 20-foot-radius sphere centered on that point must succeed on a DC 23 Dexterity saving throw or take 18 (4d8) force damage and be knocked prone.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```