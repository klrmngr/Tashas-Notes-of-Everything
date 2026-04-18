---
type: pc
race: "Dragon"
class:
 - "Sheldon the Blueberry Dragon"
subClass:
 - "CR 7"
cover: "Sheldon the Blueberry Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/mismv1
---
###### Sheldon the Blueberry Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Sheldon the Blueberry Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 18 | 17 | 14 | 16 |
| **Mod** | +4 | +1 | +4 | +3 | +2 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 12
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +7, Int +6
**Skills:** Acrobatics +7, Athletics +7, Performance +6
**Damage Resistances:** force; psychic

---

### Traits

**Space Dweller.** Sheldon can breathe normally in a vacuum.


---

### Actions

**Multiattack.** Sheldon makes either two Bite attacks, two Blueberry Fling attacks, or one of each.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 4 (1d8) psychic damage.

**Blueberry Fling.** Ranged Weapon Attack: +7 to hit, range 30 ft., one creature. *Hit:* 11 (2d6 + 4) blueberry damage.

**Jetstream Breath (Recharge 5–6).** Sheldon exhales a line of magical wind that is 60 feet long and 5 feet wide. Each creature in that area must make a DC 15 Strength saving throw. On a failed save, the creature takes 21 (6d6) force damage, is pushed 15 feet away from Sheldon, and has the prone condition. On a successful save, the creature takes half as much damage only.


---

### Bonus Actions

**Wind Dash (2/Day).** Sheldon summons a powerful gust of wind and flies up to his speed. This movement doesn't provoke opportunity attacks. At the end of this movement, each creature within 5 feet of Sheldon must succeed on a DC 15 Strength saving throw or have the prone condition, as the wind bursts around Sheldon.


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