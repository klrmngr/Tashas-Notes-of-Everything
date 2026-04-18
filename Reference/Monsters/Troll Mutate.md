---
type: pc
race: "Giant"
class:
 - "Troll Mutate"
subClass:
 - "CR 7"
cover: "Troll Mutate.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/7
  - source/bgg
---
###### Troll Mutate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Troll Mutate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 18 | 17 | 9 | 12 |
| **Mod** | +4 | +1 | +4 | +3 | -1 | +1 |

**Speed:** 30 ft., fly 30 ft. ((winged form only)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 15
**Languages:** Giant, telepathy 60 ft.
**Saving Throws:** Con +7, Int +6
**Skills:** Perception +5, Stealth +4

---

### Traits

**Mutation.** When the troll mutate is created, it gains one of four possible body mutations at random: 1, Elastic Body; 2, Psionic Mirror; 3, Spell Scarred; or 4, Winged Form. This mutation determines certain traits in this stat block.

**Amorphous (Elastic Body Only).** The mutate can move through a space as narrow as 1 inch without squeezing.

**Magic Resistance (Spell Scarred Only).** The mutate has advantage on saving throws against spells and other magical effects.

**Psychic Rebuke (Psionic Mirror Only).** If the mutate takes psychic damage, each creature within 20 feet of it takes that damage as well.

**Regeneration.** The mutate regains 10 hit points at the start of its turn. If the mutate takes acid or fire damage, this trait doesn't function at the start of the mutate's next turn. The mutate dies only if it starts its turn with 0 hit points and doesn't regenerate. If the mutate starts its turn with 0 hit points and regenerates, it randomly gains a mutation it doesn't already have (up to a maximum of four mutations).


---

### Actions

**Multiattack.** The mutate makes two Rend attacks.

**Rend.** Melee Weapon Attack: +7 to hit, reach 5 ft. (or 15 ft. if the mutate has the Elastic Body mutation), one target. *Hit:* 15 (2d10 + 4) slashing damage plus 9 (2d8) force damage.

**Psychic Burst (Recharge 5–6).** The mutate unleashes a wave of psychic energy. Each creature within 30 feet of the mutate must make a DC 14 Intelligence saving throw, taking 28 (8d6) psychic damage on a failed save, or half as much damage on a successful one.


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