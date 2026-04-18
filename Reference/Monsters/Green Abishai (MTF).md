---
type: pc
race: "Fiend (devil)"
class:
 - "Green Abishai"
subClass:
 - "CR 15"
cover: "Green Abishai.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/15
  - source/mtf
---
###### Green Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Green Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 187 (25d8 + 75) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 17 | 16 | 17 | 12 | 19 |
| **Mod** | +1 | +3 | +3 | +3 | +1 | +4 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Int +8, Cha +9
**Skills:** Deception +9, Insight +6, Perception +6, Persuasion +9
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the abishai's darkvision.

**Magic Resistance.** The abishai has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The abishai's weapon attacks are magical.


---

### Actions

**Multiattack.** The abishai makes two attacks, one with its claws and one with its longsword, or it casts one spell from its Innate Spellcasting trait and makes one claw attack.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or take 11 (2d10) poison damage and become poisoned for 1 minute. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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