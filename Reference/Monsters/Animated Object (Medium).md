---
type: pc
race: "Construct"
class:
 - "Animated Object (Medium)"
subClass:
 - "CR —"
cover: "Animated Object (Medium).png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/phb
---
###### Animated Object (Medium)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Player's Handbook
___

> [!infobox|no-t right]
> ![[Animated Object (Medium).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 40 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Player's Handbook |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 3 | 3 | 1 |
| **Mod** | +0 | +1 | +0 | -4 | -4 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 6
**Languages:** —

---

### Traits

**Animated.** If the object lacks legs or other appendages it can use for locomotion, it instead has a flying speed of 30 feet and can hover. If the object is securely attached to a surface or larger object, such as a chain bolted to a wall, its speed is 0.
When the animated object drops to 0 hit points, it reverts to its original object form, and any remaining damage carries over to its original object form.
The DM might rule that a specific objects slam attack inflicts slashing or piercing damage based on its form.


---

### Actions

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (2d6 + 1) bludgeoning damage.


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