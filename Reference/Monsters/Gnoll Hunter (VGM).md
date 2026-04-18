---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Gnoll Hunter"
subClass:
 - "CR 1/2"
cover: "Gnoll Hunter.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/vgm
---
###### Gnoll Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Gnoll Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 12 | 8 | 12 | 8 |
| **Mod** | +2 | +2 | +1 | -1 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Gnoll
**Skills:** Perception +3, Stealth +4

---

### Traits

**Rampage.** When the gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack.** The gnoll makes two melee attacks with its spear or two ranged attacks with its longbow.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Spear.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage when used with two hands to make a melee attack.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage, and the target's speed is reduced by 10 feet until the end of its next turn.


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