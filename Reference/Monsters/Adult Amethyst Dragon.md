---
type: pc
race: "Dragon (gem)"
class:
 - "Adult Amethyst Dragon"
subClass:
 - "CR 16"
cover: "Adult Amethyst Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/16
  - source/ftd
---
###### Adult Amethyst Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Adult Amethyst Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (gem) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 229 (17d12 + 119) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 14 | 25 | 20 | 17 | 21 |
| **Mod** | +7 | +2 | +7 | +5 | +3 | +5 |

**Speed:** 40 ft., fly 80 ft. ((hover)), swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +12, Wis +8, Cha +10
**Skills:** Arcana +15, Perception +13, Persuasion +10, Stealth +7
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened; prone

---

### Traits

**Amphibious.** The dragon can breathe both air and water.

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage plus 9 (2d8) force damage.

**Claw.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 11 (1d8 + 7) slashing damage.

**Singularity Breath (Recharge 5–6).** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 90-foot cone. Each creature in that area must make a DC 20 Strength saving throw. On a failed save, the creature takes 45 (10d8) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Explosive Crystal (Costs 3 Actions).** The dragon spits an amethyst that that explodes at a point it can see within 60 feet of it. Each creature within a 20-foot-radius sphere centered on that point must succeed on a DC 20 Dexterity saving throw or take 13 (3d8) force damage and be knocked prone.


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