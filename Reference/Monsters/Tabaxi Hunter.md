---
type: pc
race: "Humanoid (tabaxi)"
class:
 - "Tabaxi Hunter"
subClass:
 - "CR 1"
cover: "Tabaxi Hunter.png"
campaign:
locations:
tags:
  - race/tabaxi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/toa
---
###### Tabaxi Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Tabaxi Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tabaxi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (tabaxi) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 11 | 13 | 14 | 15 |
| **Mod** | +0 | +3 | +0 | +1 | +2 | +2 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common plus any one language
**Skills:** Athletics +2, Perception +4, Stealth +5, Survival +6

---

### Traits

**Feline Agility.** When the tabaxi moves on its turn in combat, it can double its speed until the end of the turn. Once it uses this ability, the tabaxi can't use it again until it moves 0 feet on one of its turns.


---

### Actions

**Multiattack.** The tabaxi makes two attacks with its claws, its shortsword, or its shortbow.

**Claws.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) slashing damage.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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