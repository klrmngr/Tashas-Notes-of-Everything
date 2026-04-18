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
  - source/dmg
---
###### Avatar of Death
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dungeon Master's Guide
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
> | :FasHeart: HP | half the hit point maximum of its summoner |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dungeon Master's Guide |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 16 | 16 | 16 |
| **Mod** | +3 | +3 | +3 | +3 | +3 | +3 |

**Speed:** 60 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., truesight 60 ft., passive Perception 13
**Languages:** all languages known to its summoner
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Incorporeal Movement.** The avatar can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Turn Immunity.** The avatar is immune to features that turn undead.


---

### Actions

**Reaping Scythe.** The avatar sweeps its spectral scythe through a creature within 5 feet of it, dealing 7 (1d8 + 3) slashing damage plus 4 (1d8) necrotic damage.


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