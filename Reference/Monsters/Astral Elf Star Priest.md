---
type: pc
race: "Humanoid (cleric)"
class:
 - "Astral Elf Star Priest"
subClass:
 - "CR 5"
cover: "Astral Elf Star Priest.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bam
---
###### Astral Elf Star Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Astral Elf Star Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (cleric) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (chain shirt) |
> | :FasHeart: HP | 90 (20d8) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 11 | 10 | 16 | 20 | 17 |
| **Mod** | +0 | +0 | +0 | +3 | +5 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Int +6, Wis +8, Cha +6
**Skills:** Medicine +8, Religion +6

---

### Traits

**Fey Ancestry.** The elf has advantage on saving throws it makes to avoid or end the charmed condition on itself, and magic can't put it to sleep.

**Unusual Nature.** The elf doesn't require sleep.


---

### Actions

**Multiattack.** The elf makes two Morningstar attacks. It can use Rain of Radiance in place of one of these attacks.

**Morningstar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) piercing damage plus 17 (5d6) radiant damage.

**Rain of Radiance.** Magical, flame-like radiance rains down on a creature that the elf can see within 60 feet of itself. The target must make a DC 16 Dexterity saving throw, taking 22 (5d8) radiant damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Starlight Step (2/Day).** The elf magically teleports up to 30 feet, along with anything it is wearing or carrying, to an unoccupied space it can see.


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