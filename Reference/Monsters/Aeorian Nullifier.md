---
type: pc
race: "Monstrosity"
class:
 - "Aeorian Nullifier"
subClass:
 - "CR 12"
cover: "Aeorian Nullifier.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/12
  - source/egw
---
###### Aeorian Nullifier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Aeorian Nullifier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 180 (19d10 + 76) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 18 | 7 | 14 | 18 |
| **Mod** | +4 | +2 | +4 | -2 | +2 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** understands Draconic but can't speak
**Saving Throws:** Wis +6, Cha +8
**Skills:** Perception +6, Survival +6
**Damage Immunities:** necrotic; radiant

---

### Traits

**Horrid Gnashing.** The nullifier's mouths gnash incoherently while it can see any enemies. Each creature that starts its turn within 20 feet of the nullifier and can hear it must make a DC 16 Wisdom saving throw. Unless the save succeeds, the creature rolls a d8 to determine what it does during the current turn:
- **1-4:.** The creature is stunned until the end of the turn.
- **5-6:.** The creature is frightened until the end of the turn and uses its movement to get as far as possible from the nullifier.
- **7-8:.** The creature doesn't move, and it uses its action to make one melee attack against a random creature (other than itself) if one is within reach. It otherwise does nothing

**Magic Resistance.** The nullifier has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The nullifier makes three attacks: one with its bites and two with its claws.

**Bites.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 17 (2d12 + 4) piercing damage plus 11 (2d10) force damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 11 (2d10) force damage, and the target is grappled (escape DC 16) if it's a creature. The nullifier has two claws, each of which can grapple one creature.


---

### Reactions

**Counterspell.** The nullifier attempts to interrupt a creature that it can see within 60 feet in the process of casting a spell. If the creature is casting a spell of 3rd level or lower, its spell fails and has no effect. If it is casting a spell of 4th level or higher, the nullifier makes a Charisma check with a DC equal to 10 + the spell's level. On a success, the creature's spell fails and has no effect.


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