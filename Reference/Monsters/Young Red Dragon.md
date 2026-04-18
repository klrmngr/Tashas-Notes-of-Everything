---
type: pc
race: "Dragon"
class:
 - "Young Red Dragon"
subClass:
 - "CR 10"
cover: "Young Red Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/10
  - source/mm
---
###### Young Red Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Red Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 11 | 19 |
| **Mod** | +6 | +0 | +5 | +2 | +0 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Con +9, Wis +4, Cha +8
**Skills:** Perception +8, Stealth +4
**Damage Immunities:** fire

---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 3 (1d6) fire damage.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Fire Breath (Recharge 5–6).** The dragon exhales fire in a 30-foot cone. Each creature in that area must make a DC 17 Dexterity saving throw, taking 56 (16d6) fire damage on a failed save, or half as much damage on a successful one.


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