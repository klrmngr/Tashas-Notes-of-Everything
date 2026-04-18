---
type: pc
race: "Monstrosity"
class:
 - "Two-Headed Owlbear"
subClass:
 - "CR 3"
cover: "Two-Headed Owlbear.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/imr
---
###### Two-Headed Owlbear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Two-Headed Owlbear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 17 | 3 | 12 | 7 |
| **Mod** | +5 | +1 | +3 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60, passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Two Heads.** The two-headed owlbear has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.

**Wakeful.** When one of the owlbear's heads is asleep, its other head is awake.


---

### Actions

**Multiattack.** The two-headed owlbear makes three attacks: two with its beaks and one with its claws.

**Beak.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.


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