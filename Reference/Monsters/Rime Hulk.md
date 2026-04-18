---
type: pc
race: "Elemental"
class:
 - "Rime Hulk"
subClass:
 - "CR 5"
cover: "Rime Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/bgg
---
###### Rime Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Rime Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (9d10 + 36) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 8 | 9 | 6 |
| **Mod** | +4 | +0 | +4 | -1 | -1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Aquan, Giant
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** When the rime hulk dies, it explodes in a 10-foot-radius sphere of frigid air and frost centered on itself. Each creature in that area must succeed on a DC 15 Constitution saving throw or take 10 (3d6) cold damage.


---

### Actions

**Multiattack.** The rime hulk makes two Slam attacks.

**Slam.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage plus 9 (2d8) cold damage.

**Trail of Frost (Recharge 5–6).** The rime hulk moves up to its speed without provoking opportunity attacks and can move through the space of any Medium or smaller creature. Each time the rime hulk enters another creature's space for the first time during this move, that creature must make a DC 15 Constitution saving throw. On a failed save, the creature takes 22 (4d10) cold damage, and its speed is reduced by 10 feet until the start of the rime hulk's next turn. On a successful save, the creature takes half as much damage only.


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