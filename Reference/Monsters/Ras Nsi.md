---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Ras Nsi"
subClass:
 - "CR 7"
cover: "Ras Nsi.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/7
  - source/toa
---
###### Ras Nsi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Ras Nsi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (bracers of defense) |
> | :FasHeart: HP | 127 (17d8 + 51) reduced to 107; subtract 1 for each day that passes during the adventure |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 17 | 18 | 18 | 21 |
| **Mod** | +3 | +3 | +3 | +4 | +4 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Con +6, Wis +7
**Skills:** Deception +8, Persuasion +8, Religion +7, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Special Equipment.** Ras Nsi wears bracers of defense, wields a flame tongue longsword, and carries a sending stone matched to the one carried by the guide Salida (see chapter 1).

**Shapechanger.** Ras Nsi can use his action to polymorph into a Medium snake or back into his yuan-ti form. His statistics are the same in each form. Any equipment he is wearing or carrying isn't transformed. He doesn't change form if he dies.

**Magic Resistance.** Ras Nsi has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Ras Nsi makes three melee attacks, but can use Constrict only once.

**Bite (Snake Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.

**Constrict.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 14). Until this grapple ends, the target is restrained, and Ras Nsi can't constrict another target.

**Flame Tongue Longsword (Yuan-ti Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage when used with two hands, plus 7 (2d6) fire damage.


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