---
type: pc
race: "Fiend (devil)"
class:
 - "Bone Devil"
subClass:
 - "CR 9"
cover: "Bone Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/mm
---
###### Bone Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Bone Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 18 | 13 | 14 | 16 |
| **Mod** | +4 | +3 | +4 | +1 | +2 | +3 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Int +5, Wis +6, Cha +7
**Skills:** Deception +7, Insight +6
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the devil's darkvision.

**Magic Resistance.** The devil has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes three attacks: two with its claws and one with its sting.

**Claw.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.

**Sting.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage plus 17 (5d6) poison damage, and the target must succeed on a DC 14 Constitution saving throw or become poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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