---
type: pc
race: "Dragon"
class:
 - "Young Deep Dragon"
subClass:
 - "CR 5"
cover: "Young Deep Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/5
  - source/fraif
---
###### Young Deep Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Young Deep Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 12 | 14 | 16 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +3 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 150 ft., passive Perception 18
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Dex +4, Wis +5
**Skills:** Perception +8, Stealth +7
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Slashing damage plus 3 (1d6) Poison damage.

**Nightmare Breath (Recharge 5–6).** wis DC 14, each creature in a 30-foot Cone.  22 (4d10) Psychic damage, and the target has the Frightened condition until the end of the dragon's next turn.  Half damage only.


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