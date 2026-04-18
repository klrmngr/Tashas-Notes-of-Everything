---
type: pc
race: "Giant"
class:
 - "Ogre Battering Ram"
subClass:
 - "CR 4"
cover: "Ogre Battering Ram.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/4
  - source/mtf
---
###### Ogre Battering Ram
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Ogre Battering Ram.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (ring mail) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 16 | 5 | 7 | 7 |
| **Mod** | +4 | -1 | +3 | -3 | -2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common, Giant

---

### Traits

**Siege Monster.** The ogre deals double damage to objects and structures.


---

### Actions

**Bash.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) bludgeoning damage, and the ogre can push the target 5 feet away if the target is Huge or smaller.

**Block the Path.** Until the start of the ogre's next turn, attack rolls against the ogre have disadvantage, it has advantage on the attack roll it makes for an opportunity attack, and that attack deals an extra 16 (3d10) bludgeoning damage on a hit. Also, each enemy that tries to move out of the ogre's reach without teleporting must succeed on a DC 14 Strength saving throw or have its speed reduced to 0 until the start of the ogre's next turn.


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