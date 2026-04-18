---
type: pc
race: "Beast"
class:
 - "Sky Leviathan"
subClass:
 - "CR 10"
cover: "Sky Leviathan.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/gargantuan
  - cr/10
  - source/psk
---
###### Sky Leviathan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSK
___

> [!infobox|no-t right]
> ![[Sky Leviathan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Gargantuan Beast |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 247 (15d20 + 90) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSK |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 7 | 22 | 1 | 8 | 4 |
| **Mod** | +9 | -2 | +6 | -5 | -1 | -3 |

**Speed:** fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** —
**Saving Throws:** Con +10, Wis +3

---

### Actions

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Dexterity saving throw or be swallowed by the leviathan. A swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the leviathan, and it takes 21 (6d6) acid damage at the start of each of the leviathan's turns.
If the leviathan takes 30 damage or more on a single turn from a creature inside it, the leviathan must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the leviathan. If the leviathan dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.


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