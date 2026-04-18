---
type: pc
race: "Dragon"
class:
 - "Young Bronze Dragon"
subClass:
 - "CR 8"
cover: "Young Bronze Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/8
  - source/mm
---
###### Young Bronze Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Young Bronze Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 19 | 14 | 13 | 17 |
| **Mod** | +5 | +0 | +4 | +2 | +1 | +3 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +3, Con +7, Wis +4, Cha +6
**Skills:** Insight +4, Perception +7, Stealth +3
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.

**Breath Weapons (Recharge 5–6).** The dragon uses one of the following breath weapons.
- **Lightning Breath.** The dragon exhales lightning in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 15 Dexterity saving throw, taking 55 (10d10) lightning damage on a failed save, or half as much damage on a successful one.
- **Repulsion Breath.** The dragon exhales repulsion energy in a 30-foot cone. Each creature in that area must succeed on a DC 15 Strength saving throw. On a failed save, the creature is pushed 40 feet away from the dragon.


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