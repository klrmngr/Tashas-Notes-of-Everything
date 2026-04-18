---
type: pc
race: "Monstrosity"
class:
 - "Lamia"
subClass:
 - "CR 4"
cover: "Lamia.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/mm
---
###### Lamia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Lamia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 97 (13d10 + 26) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 15 | 14 | 15 | 16 |
| **Mod** | +3 | +1 | +2 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Common
**Skills:** Deception +7, Insight +4, Stealth +3

---

### Actions

**Multiattack.** The lamia makes two attacks: one with its claws and one with its dagger or Intoxicating Touch.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) slashing damage.

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Intoxicating Touch.** Melee Spell Attack: +5 to hit, reach 5 ft., one creature. *Hit:* The target is magically cursed for 1 hour. Until the curse ends, the target has disadvantage on Wisdom saving throws and all ability checks.


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