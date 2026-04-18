---
type: pc
race: "Dragon"
class:
 - "Spirit Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Spirit Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/fraif
---
###### Spirit Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Spirit Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 15 | 14 | 11 | 14 |
| **Mod** | +2 | +1 | +2 | +2 | +0 | +2 |

**Speed:** 30 ft., burrow 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic; telepathy 120 ft.
**Saving Throws:** Dex +3, Con +4
**Skills:** Perception +2, Stealth +3
**Damage Resistances:** necrotic

---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Slashing damage plus 3 (1d6) Necrotic damage.

**Ruinous Breath (Recharge 5–6).** con DC 12, each creature in a 15-foot Cone.  13 (3d8) Necrotic damage.  Half damage.

**Time-Warping Breath.** wis DC 12, each creature that isn't currently affected by this breath in a 15-foot Cone.  The target's Speed is halved, it can't take Reactions, and it can take either an action or a Bonus Action on its turn, not both. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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