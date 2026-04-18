---
type: pc
race: "Fiend (demon)"
class:
 - "Abyssal Chicken"
subClass:
 - "CR 1/4"
cover: "Abyssal Chicken.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1-4
  - source/bgdia
---
###### Abyssal Chicken
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Abyssal Chicken.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Fiend (demon) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 13 | 4 | 9 | 5 |
| **Mod** | -2 | +2 | +1 | -3 | -1 | -3 |

**Speed:** 30 ft., fly 30 ft. ((see bad flier below)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 9
**Languages:** understands Abyssal but can't speak
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** blinded; poisoned

---

### Traits

**Bad Flier.** The abyssal chicken falls at the end of a turn if it's airborne and the only thing holding it aloft is its flying speed.


---

### Actions

**Multiattack.** The abyssal chicken makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage.

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.


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