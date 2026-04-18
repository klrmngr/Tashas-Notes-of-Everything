---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Gnoll Flesh Gnawer"
subClass:
 - "CR 1"
cover: "Gnoll Flesh Gnawer.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/vgm
---
###### Gnoll Flesh Gnawer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Gnoll Flesh Gnawer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 12 | 8 | 10 | 8 |
| **Mod** | +1 | +2 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Gnoll
**Saving Throws:** Dex +4

---

### Traits

**Rampage.** When the gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack.** The gnoll makes three attacks: one with its bite and two with its shortsword.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Sudden Rush.** Until the end of the turn, the gnoll's speed increases by 60 feet and it doesn't provoke opportunity attacks.


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