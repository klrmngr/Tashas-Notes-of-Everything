---
type: pc
race: "Humanoid (khoravar)"
class:
 - "Medani Inquisitive"
subClass:
 - "CR 3"
cover: "Medani Inquisitive.png"
campaign:
locations:
tags:
  - race/khoravar
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/efa
---
###### Medani Inquisitive
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Medani Inquisitive.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (khoravar) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (khoravar) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 15 | 16 | 14 |
| **Mod** | +2 | +0 | +2 | +2 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Saving Throws:** Con +4, Wis +5
**Skills:** Insight +5, Investigation +4

---

### Actions

**Multiattack.** The inquisitive makes three Crooked Staff attacks. It can replace one attack with a use of Inquisitive Eye.

**Crooked Staff.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition. If the target already has the Prone condition, the attack deals an extra 7 (2d6) Radiant damage.

**Inquisitive Eye.** wis DC 13, one creature the inquisitive can see within 60 feet.  10 (3d6) Psychic damage, and the target is marked. The inquisitive has Advantage on attack rolls against a target it has marked. While marked, the target can't become hidden from the inquisitive, and if it has the Invisible condition, it gains no benefit from that condition against the inquisitive. The mark disappears after 1 minute or when the inquisitive uses this action again.  Half damage only.


---

### Reactions

**Spontaneous Barrier (Recharge 4–6).**  The inquisitive or an ally it can see is hit with an attack roll.  The inquisitive adds 2 to its or the ally's AC against that attack, possibly causing it to miss.


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