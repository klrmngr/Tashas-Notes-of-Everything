---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Yuan-ti Mind Whisperer"
subClass:
 - "CR 4"
cover: "Yuan-ti Mind Whisperer.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/vgm
---
###### Yuan-ti Mind Whisperer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Yuan-ti Mind Whisperer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 14 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft. (penetrates magical darkness), passive Perception 12
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +4, Cha +5
**Skills:** Deception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The yuan-ti can use its action to polymorph into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.

**Mind Fangs (2/Day).** The first time the yuan-ti hits with a melee attack on its turn, it can deal an extra 16 (3d10) psychic damage to the target.

**Sseth's Blessing.** When the yuan-ti reduces an enemy to 0 hit points, the yuan-ti gains 9 temporary hit points.


---

### Actions

**Multiattack (Yuan-ti Form Only).** The yuan-ti makes one bite attack and one scimitar attack.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.

**Scimitar (Yuan-ti Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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