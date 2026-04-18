---
type: pc
race: "Fey"
class:
 - "Conclave Dryad"
subClass:
 - "CR 9"
cover: "Conclave Dryad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/9
  - source/ggr
---
###### Conclave Dryad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Conclave Dryad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 14 | 19 | 20 | 21 |
| **Mod** | +1 | +4 | +2 | +4 | +5 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Int +8, Wis +9, Cha +9
**Skills:** Arcana +8, Nature +8, Perception +9

---

### Traits

**Magic Resistance.** The dryad has advantage on saving throws against spells and other magical effects.

**Speak with Beasts and Plants.** The dryad can communicate with beasts and plants as if they and the dryad shared a language.


---

### Actions

**Multiattack.** The dryad makes three attacks, using its vine staff, its longbow, or both.

**Vine Staff.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Dexterity saving throw or become restrained by twisting vines for 1 minute. A target restrained in this way can use an action to make a DC 17 Strength (Athletics) or Dexterity (Acrobatics) check, ending the effect on itself on a success.

**Longbow.** Ranged Weapon Attack: +8 to hit, range 150/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Summon Mount (1/Day).** The dryad magically summons a mount, which appears in an unoccupied space within 60 feet of the dryad. The mount remains for 8 hours, until it or the dryad dies, or until the dryad dismisses it as an action. The mount uses the stat block of an [[Elk]] (see the Monster Manual) with these changes: it is a plant instead of a beast, it has an Intelligence of 6, and it understands Sylvan but can't speak. While within 1 mile of the mount, the dryad can communicate with it telepathically.

**Suppress Magic (Recharge 5–6).** The dryad targets one magic item it can see within 120 feet of it. If the magic item isn't an artifact, its magical properties are suppressed for 10 minutes, until the dryad is incapacitated or dies, or until the dryad uses a bonus action to end the effect.


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