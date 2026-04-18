---
type: pc
race: "Fiend"
class:
 - "Hellwasp"
subClass:
 - "CR 5"
cover: "Hellwasp.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/5
  - source/bgdia
---
###### Hellwasp
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Hellwasp.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 52 (8d10 + 8) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 12 | 10 | 10 | 7 |
| **Mod** | +4 | +2 | +1 | +0 | +0 | -2 |

**Speed:** 10 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Infernal, telepathy 300 ft. (with other hellwasps only)
**Saving Throws:** Dex +5, Wis +3
**Damage Vulnerabilities:** cold
**Damage Immunities:** fire

---

### Traits

**Magic Weapons.** The hellwasp's weapon attacks are magical.


---

### Actions

**Multiattack.** The hellwasp makes two attacks: one with its sting and one with its sword talons.

**Sting.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 8 (1d8 + 4) piercing damage plus 7 (2d6) fire damage, and the target must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute. While poisoned in this way, the target is also paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Sword Talons.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.


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