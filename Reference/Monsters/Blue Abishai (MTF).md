---
type: pc
race: "Fiend (devil)"
class:
 - "Blue Abishai"
subClass:
 - "CR 17"
cover: "Blue Abishai.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/17
  - source/mtf
---
###### Blue Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Blue Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 195 (26d8 + 78) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 17 | 22 | 23 | 18 |
| **Mod** | +2 | +2 | +3 | +6 | +6 | +4 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Int +12, Wis +12
**Skills:** Arcana +12
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; lightning; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the abishai's darkvision.

**Magic Resistance.** The abishai has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The abishai's weapon attacks are magical.


---

### Actions

**Multiattack.** The abishai makes two attacks: one with its quarterstaff and one with its bite.

**Quarterstaff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage if used with two hands.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d10 + 2) piercing damage plus 14 (4d6) lightning damage.


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