---
type: pc
race: "Fiend (demon)"
class:
 - "Draegloth"
subClass:
 - "CR 7"
cover: "Draegloth.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/7
  - source/vgm
---
###### Draegloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Draegloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 18 | 13 | 11 | 11 |
| **Mod** | +5 | +2 | +4 | +1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Abyssal, Elvish, Undercommon
**Skills:** Perception +3, Stealth +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Fey Ancestry.** The draegloth has advantage on saving throws against being charmed, and magic can't put it to sleep.


---

### Actions

**Multiattack.** The draegloth makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 16 (2d10 + 5) piercing damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) slashing damage.


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