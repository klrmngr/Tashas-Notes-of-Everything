---
type: pc
race: "Monstrosity (warlock)"
class:
 - "Yuan-ti Mind Whisperer"
subClass:
 - "CR 4"
cover: "Yuan-ti Mind Whisperer.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/mpmm
---
###### Yuan-ti Mind Whisperer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Yuan-ti Mind Whisperer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Monstrosity (warlock) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 14 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +4, Cha +5
**Skills:** Deception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the yuan-ti's darkvision.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.

**Sseth's Blessing.** When the yuan-ti reduces an enemy to 0 hit points, the yuan-ti gains 9 temporary hit points.


---

### Actions

**Multiattack.** The yuan-ti makes two Bite attacks and one Scimitar attack, or it makes two Spectral Fangs attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.

**Scimitar (Yuan-ti Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Spectral Fangs.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 16 (3d8 + 3) psychic damage.


---

### Bonus Actions

**Change Shape.** The yuan-ti transforms into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.


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