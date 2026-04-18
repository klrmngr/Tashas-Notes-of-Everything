---
type: pc
race: "Humanoid (tiefling)"
class:
 - "Avarice"
subClass:
 - "CR 7"
cover: "Avarice.png"
campaign:
locations:
tags:
  - race/tiefling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/idrotf
---
###### Avarice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Avarice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (tiefling) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 14 | 17 | 10 | 9 |
| **Mod** | -1 | +3 | +2 | +3 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic, Infernal, Orc, Yeti
**Saving Throws:** Int +6, Wis +3
**Skills:** Arcana +6, History +6
**Damage Resistances:** cold; fire

---

### Traits

**Icy Doom.** When Avarice dies, her corpse freezes for 9 days, during which time it can't be thawed, harmed by fire, animated, or raised from the dead.

**Special Equipment.** Avarice wields a staff of frost with 10 charges (see "Actions" below).


---

### Actions

**Fire Bolt (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 11 (2d10) fire damage.

**Staff of Frost.** While holding this staff, Avarice can expend 1 or more of its charges to cast one of the following spells from it (spell save DC 14): cone of cold (5 charges), fog cloud (1 charge), ice storm (4 charges), or wall of ice (4 charges). The staff regains 1d6 + 4 charges daily at dawn. If its last charge is expended, roll a d20; on a 1, the staff turns to water and is destroyed.


---

### Reactions

**Banishing Rebuke (Recharges after a Long Rest).** When Avarice is damaged by a creature that she can see within 60 feet of her, she can banish that creature to a frigid extradimensional prison for 1 minute. While there, the creature is incapacitated and takes 5 (1d10) cold damage at the start of each of its turns. At the end of each of its turns, the creature can make a DC 14 Charisma saving throw, escaping the prison on a success and reappearing in the space it left or in the nearest unoccupied space if that space is occupied. A creature that dies in the prison is trapped there indefinitely.


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