---
type: pc
race: "Humanoid (wizard)"
class:
 - "Astral Elf Aristocrat"
subClass:
 - "CR 8"
cover: "Astral Elf Aristocrat.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/bam
---
###### Astral Elf Aristocrat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Astral Elf Aristocrat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (elven chain) |
> | :FasHeart: HP | 103 (23d8) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 10 | 21 | 18 | 18 |
| **Mod** | +0 | +2 | +0 | +5 | +4 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Celestial, Common, Draconic, Elvish
**Saving Throws:** Int +8, Wis +7, Cha +7
**Skills:** Arcana +8, Deception +7, Insight +7, Persuasion +7

---

### Traits

**Fey Ancestry.** The elf has advantage on saving throws it makes to avoid or end the charmed condition on itself, and magic can't put it to sleep.

**Special Equipment.** The elf wears a suit of elven chain.

**Unusual Nature.** The elf doesn't require sleep.


---

### Actions

**Multiattack.** The elf makes two Scimitar attacks and uses Radiant Beam (if available).

**Scimitar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage plus 10 (3d6) radiant damage.

**Radiant Beam (3/Day).** A magical beam of radiance flashes out from the elf's hand in a 5-foot-wide, 60-foot-long line. Each creature in the line must make a DC 16 Constitution saving throw, taking 18 (4d8) radiant damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Starlight Step (3/Day).** The elf magically teleports up to 30 feet, along with anything it is wearing or carrying, to an unoccupied space it can see.

**Summon Solar Dragon (1/Day).** The elf has a 50 percent chance of magically summoning a [[Young Solar Dragon]]. A summoned dragon appears in an unoccupied space that the summoner can see, acts on its own initiative count, and is an ally of its summoner. It remains for 10 minutes, until it or its summoner dies, or until its summoner dismisses it as an action.


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