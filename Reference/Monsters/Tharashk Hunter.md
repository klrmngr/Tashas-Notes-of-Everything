---
type: pc
race: "Humanoid (human, orc)"
class:
 - "Tharashk Hunter"
subClass:
 - "CR 6"
cover: "Tharashk Hunter.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/efa
---
###### Tharashk Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Tharashk Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (human, orc) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (human, orc) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 15 | 11 | 16 | 10 |
| **Mod** | +1 | +4 | +2 | +0 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 16
**Languages:** Common, Orc plus one other language
**Saving Throws:** Dex +7, Con +5
**Skills:** Perception +6, Stealth +7, Survival +6

---

### Actions

**Multiattack.** The hunter makes three attacks, using Shortsword or Longbow in any combination.

**Shortsword.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage, and the target has Disadvantage on attack rolls and ability checks until the end of its next turn.

**Longbow.** r +7, range 150/600 ft. *Hit:* 17 (3d8 + 4) Piercing damage, and the target's Speed is reduced by 10 feet until the end of its next turn.


---

### Bonus Actions

**Mark of Tharashk.** The hunter magically marks one creature it can see within 150 feet. The mark lasts for 1 hour, until the target dies, or until the hunter uses this Bonus Action again. While the target is marked in this way, the hunter has Advantage on attack rolls against the target, and the target gains no benefit from the Invisible condition against the hunter.


---

### Reactions

**Uncanny Dodge.**  The hunter is hit by an attack roll.  The hunter halves the damage (round down) it takes from that attack.


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