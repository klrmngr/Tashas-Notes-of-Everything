---
type: pc
race: "Giant"
class:
 - "Ogre Bolt Launcher"
subClass:
 - "CR 2"
cover: "Ogre Bolt Launcher.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/2
  - source/mpmm
---
###### Ogre Bolt Launcher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Ogre Bolt Launcher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 16 | 5 | 7 | 7 |
| **Mod** | +4 | +1 | +3 | -3 | -2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common, Giant

---

### Actions

**Fist.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage.

**Bolt Launcher.** Ranged Weapon Attack: +3 to hit, range 120/480 ft., one target. *Hit:* 17 (3d10 + 1) piercing damage.


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