---
type: pc
race: "Aberration"
class:
 - "Esthetic"
subClass:
 - "CR 12"
cover: "Esthetic.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/gargantuan
  - cr/12
  - source/bam
---
###### Esthetic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Esthetic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Gargantuan Aberration |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 217 (14d20 + 70) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 8 | 20 | 1 | 10 | 1 |
| **Mod** | +7 | -1 | +5 | -5 | +0 | -5 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 300 ft. (blind beyond this radius), passive Perception 12
**Languages:** —
**Damage Immunities:** acid
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; petrified; prone

---

### Traits

**Bioluminescence.** While it has at least 1 hit point, the esthetic sheds bright light in a 30-foot radius and dim light for an additional 30 feet, and its interior compartments are dimly lit.

**Spelljamming.** The esthetic has the properties of a spelljamming helm (see the Astral Adventurer's Guide), but only its reigar creator can attune to it.

**Unusual Nature.** The esthetic doesn't require air, food, or drink.


---

### Actions

**Multiattack.** The esthetic makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +11 to hit, reach 30 ft., one target. *Hit:* 17 (3d6 + 7) force damage, and if the target is a creature, it is grappled (escape DC 17). Until this grapple ends, the creature takes 18 (4d8) acid damage at the start of each of its turns, and the esthetic can't use this tentacle against other targets. The esthetic has 1d4 × 2 tentacles, each of which can grapple one target.


---

### Bonus Actions

**Jammerscream (Recharge 6).** The esthetic targets one spelljamming ship within 300 feet of itself, magically suppressing the properties of the ship's spelljamming helm for 2d10 days. If the ship has more than one helm aboard it, randomly determine which helm is affected. A creature attuned to that helm can choose to make a DC 17 Charisma saving throw. On a failed save, the creature takes 42 (12d6) psychic damage, and the helm is suppressed for 2d10 hours instead of 2d10 days. On a successful save, the creature takes half as much damage, and the helm is suppressed for 2d10 minutes instead of 2d10 days.


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