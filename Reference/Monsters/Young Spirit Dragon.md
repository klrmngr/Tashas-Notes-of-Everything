---
type: pc
race: "Dragon"
class:
 - "Young Spirit Dragon"
subClass:
 - "CR 8"
cover: "Young Spirit Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/8
  - source/fraif
---
###### Young Spirit Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Young Spirit Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 152 (16d10 + 64) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 19 | 17 | 14 | 16 |
| **Mod** | +4 | +1 | +4 | +3 | +2 | +3 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 15
**Languages:** Common, Draconic; telepathy 120 ft.
**Saving Throws:** Dex +4, Con +7
**Skills:** Insight +5, Perception +5, Stealth +4
**Damage Resistances:** necrotic

---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Time-Warping Breath.

**Rend.** m +7, reach 10 ft. *Hit:* 14 (3d6 + 4) Slashing damage plus 7 (2d6) Necrotic damage.

**Ruinous Breath (Recharge 5–6).** con DC 15, each creature in a 30-foot Cone.  36 (8d8) Necrotic damage.  Half damage.

**Time-Warping Breath.** wis DC 15, each creature that isn't currently affected by this breath in a 30-foot Cone.  The target's Speed is halved, it can't take Reactions, and it can take either an action or a Bonus Action on its turn, not both. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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