---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Yuan-ti Abomination"
subClass:
 - "CR 7"
cover: "Yuan-ti Abomination.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/mm
---
###### Yuan-ti Abomination
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Yuan-ti Abomination.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 17 | 15 | 18 |
| **Mod** | +4 | +3 | +3 | +3 | +2 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Common, Draconic
**Skills:** Perception +5, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The yuan-ti can use its action to polymorph into a Large snake, or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It doesn't change form if it dies.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack (Abomination Form Only).** The yuan-ti makes two ranged attacks or three melee attacks, but can use its bite and constrict attacks only once each.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 7 (1d6 + 4) piercing damage plus 10 (3d6) poison damage.

**Constrict.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage, and the target is grappled (escape DC 14). Until this grapple ends, the target is restrained, and the yuan-ti can't constrict another target.

**Scimitar (Abomination Form Only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Longbow (Abomination Form Only).** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage plus 10 (3d6) poison damage.


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