---
type: pc
race: "Monstrosity"
class:
 - "Trapper"
subClass:
 - "CR 3"
cover: "Trapper.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/mpmm
---
###### Trapper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Trapper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 17 | 2 | 13 | 4 |
| **Mod** | +3 | +0 | +3 | -4 | +1 | -3 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 11
**Languages:** —
**Skills:** Stealth +2

---

### Traits

**False Appearance.** If the trapper is motionless on a floor, wall, or ceiling at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the trapper move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the trapper isn't part of the floor, wall, or ceiling.

**Spider Climb.** The trapper can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Smother.** One Large or smaller creature within 10 feet of the trapper must succeed on a DC 13 Dexterity saving throw or be grappled (escape DC 14). Until the grapple ends, the target takes 13 (3d6 + 3) bludgeoning damage plus 3 (1d6) acid damage at the start of each of its turns. While grappled in this way, the target is restrained, blinded, and deprived of air. The trapper can smother only one creature at a time.


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