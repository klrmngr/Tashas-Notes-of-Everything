---
type: pc
race: "Construct"
class:
 - "Animated Object (Large)"
subClass:
 - "CR —"
cover: "Animated Object (Large).png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/—
  - source/phb
---
###### Animated Object (Large)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Player's Handbook
___

> [!infobox|no-t right]
> ![[Animated Object (Large).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 (natural armor) |
> | :FasHeart: HP | 50 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Player's Handbook |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 10 | 3 | 3 | 1 |
| **Mod** | +2 | +0 | +0 | -4 | -4 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 6
**Languages:** —

---

### Traits

**Animated.** If the object lacks legs or other appendages it can use for locomotion, it instead has a flying speed of 30 feet and can hover. If the object is securely attached to a surface or larger object, such as a chain bolted to a wall, its speed is 0.
When the animated object drops to 0 hit points, it reverts to its original object form, and any remaining damage carries over to its original object form.
The DM might rule that a specific objects slam attack inflicts slashing or piercing damage based on its form.


---

### Actions

**Slam.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d10 + 2) bludgeoning damage.


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