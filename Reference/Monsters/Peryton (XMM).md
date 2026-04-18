---
type: pc
race: "Monstrosity"
class:
 - "Peryton"
subClass:
 - "CR 2"
cover: "Peryton.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/xmm
---
###### Peryton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Peryton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 13 | 9 | 12 | 10 |
| **Mod** | +3 | +1 | +1 | -1 | +1 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** understands Common and Elvish but can't speak
**Skills:** Perception +5, Stealth +3

---

### Traits

**Flyby.** The peryton doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The peryton makes one Gore attack and one Talons attack.

**Gore.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage. If the peryton moved 30+ feet straight toward the target immediately before the hit, the target takes an extra 9 (2d8) Piercing damage.

**Talons.** m +5, reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing damage. If the attack reduces a Humanoid target to 0 Hit Points, the peryton kills the target by removing its heart.


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