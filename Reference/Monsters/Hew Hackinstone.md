---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Hew Hackinstone"
subClass:
 - "CR 2"
cover: "Hew Hackinstone.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/toa
---
###### Hew Hackinstone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Hew Hackinstone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 9 | 11 | 9 |
| **Mod** | +3 | +1 | +3 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** any one language (usually Common)
**Skills:** Survival +4
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Hew has resistance to poison damage and advantage on saving throws against being poisoned.

**Reckless.** At the start of his turn, Hew can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against him have advantage until the start of his next turn.


---

### Actions

**Battleaxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.


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