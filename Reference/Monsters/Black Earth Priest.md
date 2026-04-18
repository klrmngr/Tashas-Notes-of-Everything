---
type: pc
race: "Humanoid (human)"
class:
 - "Black Earth Priest"
subClass:
 - "CR 3"
cover: "Black Earth Priest.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/pota
---
###### Black Earth Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Black Earth Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 11 | 14 | 12 | 10 | 16 |
| **Mod** | +2 | +0 | +2 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Terran
**Skills:** Intimidation +5, Religion +3, Persuasion +5

---

### Actions

**Multiattack.** The priest makes two melee attacks.

**Glaive.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 7 (1d10 + 2) slashing damage.


---

### Reactions

**Unyielding.** When the priest is subjected to an effect that would move it, knock it prone, or both, it can use its reaction to be neither moved nor knocked prone.


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