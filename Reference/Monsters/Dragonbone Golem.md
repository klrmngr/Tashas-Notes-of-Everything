---
type: pc
race: "Construct"
class:
 - "Dragonbone Golem"
subClass:
 - "CR 11"
cover: "Dragonbone Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/11
  - source/ftd
---
###### Dragonbone Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonbone Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 161 (19d10 + 57) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 17 | 3 | 11 | 10 |
| **Mod** | +5 | +0 | +3 | -4 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands Draconic and the languages of its creator but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Fear Aura.** Each creature of the golem's choice that starts its turn within 20 feet of the golem must make a DC 15 Wisdom saving throw unless the golem is incapacitated. On a failed save, the creature is frightened until the start of its next turn. On a successful save, the creature is immune to this golem's Fear Aura for the next 24 hours.

**Magic Resistance.** The golem has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The golem doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The golem makes one Pinion attack and two Rend attacks.

**Pinion.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage. If the target is a Medium or smaller creature, it is pinned beneath the bony pinion and restrained. The golem has two pinions, each of which can restrain one target. If a creature is restrained by one of the pinions, the golem can't attack with it. Any creature restrained by a pinion can free itself at the start of its turn with a successful DC 17 Strength (Athletics) check.

**Rend.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 5 (1d10) necrotic damage.

**Petrifying Breath (Recharge 5–6).** The golem emits a 60-foot cone of petrifying gas from its mouth. Each creature in that area must succeed on a DC 15 Constitution saving throw or take 35 (10d6) poison damage and be restrained as it begins to turn to stone. The restrained target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target is petrified.


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