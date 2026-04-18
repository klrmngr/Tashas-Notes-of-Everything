---
type: pc
race: "Dragon"
class:
 - "Deep Dragon Wyrmling"
subClass:
 - "CR 1"
cover: "Deep Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/1
  - source/fraif
---
###### Deep Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Deep Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 12 | 11 | 12 | 13 |
| **Mod** | +2 | +0 | +1 | +0 | +1 | +1 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 15
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +3
**Skills:** Perception +5, Stealth +4
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage.

**Nightmare Breath (Recharge 5–6).** wis DC 11, each creature in a 15-foot Cone.  7 (2d6) Psychic damage, and the target has the Frightened condition until the end of the dragon's next turn.  Half damage only.


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