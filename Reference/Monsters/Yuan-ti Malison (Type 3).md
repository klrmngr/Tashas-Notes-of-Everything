---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Yuan-ti Malison (Type 3)"
subClass:
 - "CR 3"
cover: "Yuan-ti Malison (Type 3).png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mm
---
###### Yuan-ti Malison (Type 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Yuan-ti Malison (Type 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 12 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Abyssal, Common, Draconic
**Skills:** Deception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The yuan-ti can use its action to polymorph into a Medium snake, or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It doesn't change form if it dies.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.

**Malison Type.** The yuan-ti has one of the following types:
- **Type 1:.** Human body with snake head
- **Type 2:.** Human head and body with snakes for arms
- **Type 3:.** Human head and upper body with a serpentine lower body instead of legs


---

### Actions

**Multiattack (Yuan-ti Form Only).** The yuan-ti makes two ranged attacks or two melee attacks, but can constrict only once.

**Bite (Snake Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.

**Constrict.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 13). Until this grapple ends, the target is restrained, and the yuan-ti can't constrict another target.

**Scimitar (Yuan-ti Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Longbow (Yuan-ti Form Only).** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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