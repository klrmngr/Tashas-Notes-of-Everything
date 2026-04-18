---
type: pc
race: "Fiend (devil)"
class:
 - "Black Abishai"
subClass:
 - "CR 7"
cover: "Black Abishai.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/7
  - source/mtf
---
###### Black Abishai
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Black Abishai.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 14 | 13 | 16 | 11 |
| **Mod** | +2 | +3 | +2 | +1 | +3 | +0 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +6, Wis +6
**Skills:** Perception +6, Stealth +6
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** acid; fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the abishai's darkvision.

**Magic Resistance.** The abishai has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The abishai's weapon attacks are magical.

**Shadow Stealth.** While in dim light or darkness, the abishai can take the Hide action as a bonus action.


---

### Actions

**Multiattack.** The abishai makes three attacks: two with its scimitar and one with its bite.

**Scimitar.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 9 (2d8) acid damage.

**Creeping Darkness (Recharge 6).** The abishai casts darkness at a point within 120 feet of it, requiring no components. Wisdom is its spellcasting ability for this spell. While the spell persists, the abishai can move the area of darkness up to 60 feet as a bonus action.


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