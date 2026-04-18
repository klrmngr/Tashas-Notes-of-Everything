---
type: pc
race: "Dragon"
class:
 - "Young Black Dragon"
subClass:
 - "CR 7"
cover: "Young Black Dragon.png"
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
###### Young Black Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Black Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +2 | +3 | +1 | +0 | +2 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Con +6, Wis +3, Cha +5
**Skills:** Perception +6, Stealth +5
**Damage Immunities:** acid

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage plus 4 (1d8) acid damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Acid Breath (Recharge 5–6).** The dragon exhales acid in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw, taking 49 (11d8) acid damage on a failed save, or half as much damage on a successful one.


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