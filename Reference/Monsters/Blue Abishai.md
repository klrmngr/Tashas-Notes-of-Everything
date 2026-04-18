---
type: pc
race: "Fiend (devil, wizard)"
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
  - source/mpmm
---
###### Blue Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Blue Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 202 (27d8 + 81) |
> | :FasUserGroup: Race | Fiend (devil, wizard) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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


---

### Actions

**Multiattack.** The abishai makes three Bite or Lightning Strike attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d10 + 2) piercing damage plus 14 (4d6) lightning damage.

**Lightning Strike.** Ranged Spell Attack: +12 to hit, range 120 ft., one target. *Hit:* 36 (8d8) lightning damage.


---

### Bonus Actions

**Teleport.** The abishai teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space that it can see.


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