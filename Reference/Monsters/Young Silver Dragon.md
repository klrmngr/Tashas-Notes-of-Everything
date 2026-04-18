---
type: pc
race: "Dragon"
class:
 - "Young Silver Dragon"
subClass:
 - "CR 9"
cover: "Young Silver Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/mm
---
###### Young Silver Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Silver Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 168 (16d10 + 80) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 11 | 19 |
| **Mod** | +6 | +0 | +5 | +2 | +0 | +4 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Con +9, Wis +4, Cha +8
**Skills:** Arcana +6, History +6, Perception +8, Stealth +4
**Damage Immunities:** cold

---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Breath Weapons (Recharge 5–6).** The dragon uses one of the following breath weapons.
- **Cold Breath.** The dragon exhales an icy blast in a 30-foot cone. Each creature in that area must make a DC 17 Constitution saving throw, taking 54 (12d8) cold damage on a failed save, or half as much damage on a successful one.
- **Paralyzing Breath.** The dragon exhales paralyzing gas in a 30-foot cone. Each creature in that area must succeed on a DC 17 Constitution saving throw or be paralyzed for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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