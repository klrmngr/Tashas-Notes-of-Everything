---
type: pc
race: "Humanoid (any race)"
class:
 - "Blood Hunter"
subClass:
 - "CR 5"
cover: "Blood Hunter.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/egw
---
###### Blood Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Blood Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (half plate) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 15 | 9 | 16 | 11 |
| **Mod** | +4 | +1 | +2 | -1 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** any one language (usually Common)
**Saving Throws:** Str +7, Wis +6
**Skills:** Acrobatics +4, Insight +6, Perception +6

---

### Traits

**Blood Curse of Binding (1/Day).** As a bonus action, the blood hunter targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Strength saving throw or have its speed reduced to 0 and be unable to take reactions. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Blood Frenzy.** The blood hunter has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Magic Resistance.** The blood hunter has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The blood hunter attacks twice with a weapon.

**Greatsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 3 (1d6) fire damage.

**Heavy Crossbow.** Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage.


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