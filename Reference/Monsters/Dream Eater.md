---
type: pc
race: "Aberration"
class:
 - "Dream Eater"
subClass:
 - "CR 7"
cover: "Dream Eater.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/7
  - source/mcv2dc
---
###### Dream Eater
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Dream Eater.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 77 (14d8 + 14) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 20 | 13 | 12 | 16 | 21 |
| **Mod** | +2 | +5 | +1 | +1 | +3 | +5 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 13
**Languages:** Deep Speech, telepathy 120 ft.
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; frightened; grappled; paralyzed; petrified; restrained

---

### Traits

**Ghastly Visions.** Each creature that starts its turn within 30 feet of the dream eater must make a DC 16 Wisdom saving throw. On a failed save, the creature is frightened of the dream eater until the start of the creature's next turn. If a creature's saving throw is successful, the creature is immune to this dream eater's Ghastly Visions trait for the next 24 hours.

**Incorporeal Movement.** The dream eater can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Magic Resistance.** The dream eater has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The dream eater makes two Ensnaring Shriek attacks.

**Ensnaring Shriek.** Melee or Ranged Spell Attack: +8 to hit, reach 15 ft. or range 60 ft., one target. *Hit:* 12 (2d6 + 5) psychic damage, and if the target is a Medium or smaller creature, the target must succeed on a DC 16 Charisma saving throw or be pulled up to 15 feet toward the dream eater.


---

### Bonus Actions

**Engulfing Nightmare.** The dream eater targets one creature within 5 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or be engulfed by the dream eater, as the dream eater envelops the creature in a miasma of its worst fears.
When the dream eater engulfs a target, the dream eater enters its space, and the target immediately takes 10 (3d6) psychic damage. An engulfed target is restrained and blinded, and it takes an additional 10 (3d6) psychic damage at the start of each of the dream eater's turns. When the dream eater moves, the engulfed target moves with it.
The dream eater can have only one target engulfed at a time. An engulfed target escapes at the start of its turn by making a DC 16 Wisdom saving throw. On a successful save, the target escapes; the target is no longer engulfed, and it enters a space of its choice within 5 feet of the dream eater. A creature within 15 feet of the dream eater also can use its action to attempt to free an engulfed target. Doing so requires the creature to use its action to make a DC 16 Charisma (Persuasion) check to convince the engulfed target the nightmare isn't real, with the target escaping on a success. The creature making the check takes 10 (3d6) psychic damage, regardless of the check's success or failure, as its mind brushes against the nightmare.


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