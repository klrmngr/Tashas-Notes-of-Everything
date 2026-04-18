---
type: pc
race: "Dragon"
class:
 - "Young Copper Dragon"
subClass:
 - "CR 7"
cover: "Young Copper Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/mm
---
###### Young Copper Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Copper Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 17 | 16 | 13 | 15 |
| **Mod** | +4 | +1 | +3 | +3 | +1 | +2 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Con +6, Wis +4, Cha +5
**Skills:** Deception +5, Perception +7, Stealth +4
**Damage Immunities:** acid

---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Breath Weapons (Recharge 5–6).** The dragon uses one of the following breath weapons.
- **Acid Breath.** The dragon exhales acid in a 40-foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw, taking 40 (9d8) acid damage on a failed save, or half as much damage on a successful one.
- **Slowing Breath.** The dragon exhales gas in a 30-foot cone. Each creature in that area must succeed on a DC 14 Constitution saving throw. On a failed save, the creature can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the creature can use either an action or a bonus action on its turn, but not both. These effects last for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself with a successful save.


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