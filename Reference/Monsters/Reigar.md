---
type: pc
race: "Celestial"
class:
 - "Reigar"
subClass:
 - "CR 8"
cover: "Reigar.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/8
  - source/bam
---
###### Reigar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Reigar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (glory) |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 12 | 19 | 16 | 24 |
| **Mod** | +4 | +2 | +1 | +4 | +3 | +7 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Celestial, Common, Deep Speech, Draconic
**Saving Throws:** Dex +5, Con +4, Wis +6, Cha +10
**Skills:** Arcana +7, History +7, Performance +10, Persuasion +10

---

### Traits

**Glory.** The reigar's Armor Class includes its Charisma modifier.

**Hold Breath.** The reigar can hold its breath for 1 hour.

**Special Equipment.** The reigar wears a talarith.


---

### Actions

**Multiattack.** The reigar makes two Trident attacks.

**Trident.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage if used with two hands to make a melee attack, plus 3 (1d6) force damage if the reigar is wearing its talarith.

**Chromatic Bolt.** Ranged Spell Attack: +10 to hit, range 90 ft., one target. *Hit:* 22 (5d8) damage of a type chosen by the reigar from the following list: cold, fire, lightning, or radiant.

**Summon Duplicate (Recharges after a Short or Long Rest).** Using its talarith, the reigar summons a duplicate of itself. The duplicate obeys the reigar's commands and uses the reigar's statistics, except it is an unaligned Construct that doesn't have a talarith of its own. The duplicate takes its turn immediately after the reigar. It vanishes after 1 hour or when it is reduced to 0 hit points.


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