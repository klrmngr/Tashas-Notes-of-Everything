---
type: pc
race: "Undead"
class:
 - "Avatar of Death"
subClass:
 - "CR —"
cover: "Avatar of Death.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/—
  - source/xdmg
---
###### Avatar of Death
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XDMG
___

> [!infobox|no-t right]
> ![[Avatar of Death.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | Half the HP maximum of its summoner |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XDMG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 16 | 16 | 16 |
| **Mod** | +3 | +3 | +3 | +3 | +3 | +3 |

**Speed:** 60 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 13
**Languages:** all languages known to its summoner
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Incorporeal Movement.** The avatar can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The avatar makes a number of Reaping Scythe attacks equal to half the summoner's Proficiency Bonus (rounded up).

**Reaping Scythe.** m Automatic hit, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage plus 4 (1d8) Necrotic damage.


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