---
type: pc
race: "Humanoid (human)"
class:
 - "Cornelius Watson"
subClass:
 - "CR 12"
cover: "Cornelius Watson.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/mabjov
---
###### Cornelius Watson
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Cornelius Watson.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 154 (28d8 + 28) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 20 | 15 | 16 |
| **Mod** | +0 | +2 | +1 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Celestial, Common, Dwarvish, Gnomish, Halfling, Infernal
**Saving Throws:** Int +9, Wis +6
**Skills:** Arcana +13, History +13, Investigation +13, Perception +6

---

### Traits

**Magic Resistance.** Doc Watson has advantage on saving throws against spells and other magical effects.

**Portent (Recharge 6).** When Doc Watson or a creature he can see makes an attack roll, a saving throw, or an ability check, Doc Watson can roll a d20 and choose to use this roll in place of the attack roll, saving throw, or ability check. This trait recharges after using the Spellcasting action.


---

### Actions

**Multiattack.** Doc Watson makes three Arcane Burst attacks.

**Arcane Burst.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 32 (5d10 + 5) lightning damage.


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