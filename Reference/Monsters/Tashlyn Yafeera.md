---
type: pc
race: "Humanoid (human)"
class:
 - "Tashlyn Yafeera"
subClass:
 - "CR 9"
cover: "Tashlyn Yafeera.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Tashlyn Yafeera
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Tashlyn Yafeera.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 149 (23d8 + 46) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 14 | 10 | 14 | 12 |
| **Mod** | +4 | +2 | +2 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Saving Throws:** Str +8, Con +6
**Skills:** Athletics +8, Intimidation +5, Perception +6

---

### Traits

**Indomitable (2/Day).** Tashlyn can reroll a saving throw that she fails. She must use the new roll.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, Tashlyn can regain 20 hit points.

**Extra Damage.** Tashlyn deals an extra 7 (2d6) damage to every hit if she has more than half her hit points remaining.


---

### Actions

**Multiattack.** Tashlyn makes three attacks with her greatsword or her shortbow.

**Greatsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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