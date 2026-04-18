---
type: pc
race: "Fiend (devil)"
class:
 - "White Abishai"
subClass:
 - "CR 6"
cover: "White Abishai.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/6
  - source/mtf
---
###### White Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[White Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 68 (8d8 + 32) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 18 | 11 | 12 | 13 |
| **Mod** | +3 | +0 | +4 | +0 | +1 | +1 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +6, Con +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the abishai's darkvision.

**Magic Resistance.** The abishai has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The abishai's weapon attacks are magical.

**Reckless.** At the start of its turn, the abishai can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.


---

### Actions

**Multiattack.** The abishai makes two attacks: one with its longsword and one with its claw.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) slashing damage.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 3 (1d6) cold damage.


---

### Reactions

**Vicious Reprisal.** In response to taking damage, the abishai makes a bite attack against a random creature within 5 feet of it. If no creature is within reach, the abishai moves up to half its speed toward an enemy it can see, without provoking opportunity attacks.


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