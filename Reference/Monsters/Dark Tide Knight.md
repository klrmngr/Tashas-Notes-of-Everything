---
type: pc
race: "Humanoid (human)"
class:
 - "Dark Tide Knight"
subClass:
 - "CR 3"
cover: "Dark Tide Knight.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/pota
---
###### Dark Tide Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Dark Tide Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 14 | 10 | 11 | 11 |
| **Mod** | +3 | +3 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Skills:** Athletics +7, Stealth +7

---

### Traits

**Bonded Mount.** The knight is magically bound to a beast with an innate swimming speed trained to serve as its mount. While mounted on this beast, the knight gains the beast's senses and ability to breathe underwater. The bonded mount obeys the knight's commands. If its mount dies, the knight can train a new beast to serve as its bonded mount, a process requiring a month.

**Sneak Attack.** The knight deals an extra 7 (2d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the knight that isn't incapacitated and the knight doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** The knight makes two shortsword attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Lance.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 9 (1d12 + 3) piercing damage.


---

### Reactions

**Uncanny Dodge.** When an attacker the knight can see hits it with an attack, the knight can halve the damage against it.


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