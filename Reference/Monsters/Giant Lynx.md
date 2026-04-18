---
type: pc
race: "Fey"
class:
 - "Giant Lynx"
subClass:
 - "CR 1/2"
cover: "Giant Lynx.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1-2
  - source/bgg
---
###### Giant Lynx
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Giant Lynx.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 13 | 12 | 14 | 10 |
| **Mod** | +2 | +4 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 16
**Languages:** Giant, Sylvan
**Skills:** Perception +6, Stealth +6
**Damage Resistances:** cold

---

### Traits

**Lynx's Sight (1/Day).** The lynx can cast clairvoyance, requiring no spell components and using Wisdom as the spellcasting ability.

**Woodland Camouflage.** The lynx has advantage on Dexterity (Stealth) checks made to hide in undergrowth or snowy terrain.


---

### Actions

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage. If the lynx moved at least 20 feet straight toward the target immediately before the hit, the target must succeed on a DC 12 Strength saving throw or have the prone condition. If the target has the prone condition, the lynx can make another Claws attack against it as a bonus action.


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