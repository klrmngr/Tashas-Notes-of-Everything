---
type: pc
race: "Plant"
class:
 - "Jammer Leech"
subClass:
 - "CR 1"
cover: "Jammer Leech.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/tiny
  - cr/1
  - source/bam
---
###### Jammer Leech
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Jammer Leech.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Plant |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 27 (5d4 + 15) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 1 | 16 | 1 | 10 | 1 |
| **Mod** | +0 | -5 | +3 | -5 | +0 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** —
**Condition Immunities:** charmed; frightened; prone

---

### Traits

**Spelljammer Overload.** If the leech is reduced to 0 hit points while attached to a ship that has a spelljamming helm, the creature attuned to that helm must make a DC 13 Constitution saving throw. On a failed save, the creature takes 10 (4d4) psychic damage and is incapacitated for 1 minute. On a successful save, the creature takes half as much damage and is incapacitated until the end of its next turn.

**Unusual Nature.** The leech doesn't require air or sleep.


---

### Actions

**Spiked Tentacle.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) piercing damage.


---

### Bonus Actions

**Attach to Hull.** The leech attaches itself to a ship's hull in its space, dealing 2 (1d4) piercing damage to the ship (ignoring the ship's damage threshold). This damage can't be repaired until the leech is scraped off the hull. While the leech is attached, its speed is 0, and it can detach itself as a bonus action. As an action, a creature within reach of the leech can to try to scrape it off the hull, doing so with a successful DC 18 Strength check. On a failed check, the action is wasted as the leech remains attached to the hull. Removing the leech in this way deals no damage to the leech or the ship.


---

### Reactions

**Magical Discharge (1/Day).** When it takes damage, the leech can discharge a bolt of magical energy from its eye that targets one creature it can see within 30 feet of itself. The target must succeed on a DC 13 Dexterity saving throw or take 10 (3d6) force damage and be stunned until the end of its next turn.


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