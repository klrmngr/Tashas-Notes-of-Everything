---
type: pc
race: "Humanoid (gnome)"
class:
 - "Erky Timbers"
subClass:
 - "CR 1/4"
cover: "Erky Timbers.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/tftyp
---
###### Erky Timbers
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Erky Timbers.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnome) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 14 | 11 |
| **Mod** | +0 | +0 | +0 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic, Gnomish, Goblin
**Skills:** Medicine +4, Religion +2

---

### Actions

**Club.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.

**Channel Divinity: Turn Undead (1/Short Rest).** Erky presents his holy Symbol and speaks a prayer censuring the Undead. Each Undead that can see or hear Erky within 30 feet of him must make a DC 12 Wisdom saving throw. If the creature fails its saving throw, it is turned for 1 minute or until it takes any damage.
A turned creature must spend its turns trying to move as far away from Erky as it can, and it can't willingly move to a space within 30 feet of him. It also can't take reactions. For its action, it can use only the Dash action or try to escape from an effect that prevents it from moving. If there's nowhere to move, the creature can use the Dodge action.


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