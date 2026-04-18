---
type: pc
race: "Construct"
class:
 - "Autognome"
subClass:
 - "CR 2"
cover: "Autognome.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/2
  - source/bam
---
###### Autognome
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Autognome.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 39 (6d6 + 18) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 6 | 16 | 4 | 11 | 6 |
| **Mod** | +1 | -2 | +3 | -3 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Gnomish
**Saving Throws:** Con +5, Wis +2, Cha +0
**Damage Immunities:** poison
**Condition Immunities:** paralyzed; petrified; poisoned

---

### Traits

**Malfunction.** Whenever the autognome takes 15 damage or more from a single source and isn't reduced to 0 hit points by that damage, roll a d20 to determine if it suffers a malfunction:
- **1-10: "All Fine Here!".** No malfunction occurs.
- **11-12: "My Mind Is Going. I Can Feel It.".** The autognome is incapacitated for 1 minute.
- **13-14: "You've Disarmed Me!".** One of the autognome's arms falls off, reducing the number of Shock attacks it can make by 1 until a creature uses an action to reattach the arm.
- **15-16: "Who Turned Out the Lights?".** The autognome's head falls off and deactivates, causing the autognome to be blinded and deafened until a creature uses an action to reattach the head, which reactivates it.
- **17-20: "Have a Magical Day!".** The autognome explodes and is destroyed. Each creature within 20 feet of the exploding autognome must make a DC 11 Dexterity saving throw, taking 22 (4d10) slashing damage on a failed save, or half as much damage on a successful one.
- **Unusual Nature.** The autognome doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The autognome makes two Shock attacks.

**Shock.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (2d6) lightning damage.


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