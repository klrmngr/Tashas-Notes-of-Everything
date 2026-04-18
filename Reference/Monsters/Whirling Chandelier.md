---
type: pc
race: "Construct"
class:
 - "Whirling Chandelier"
subClass:
 - "CR 7"
cover: "Whirling Chandelier.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/7
  - source/veor
---
###### Whirling Chandelier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Whirling Chandelier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 105 (14d10 + 28) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 15 | 3 | 5 | 1 |
| **Mod** | +4 | +2 | +2 | -4 | -3 | -5 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 7
**Languages:** understands Common but can't speak
**Damage Resistances:** fire
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** If the chandelier is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the chandelier move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the chandelier is animate.

**Fiery Aura.** Any creature that starts its turn within 5 feet of the chandelier takes 7 (2d6) fire damage.


---

### Actions

**Multiattack.** The chandelier makes three Chain attacks, three Lamp attacks, or a combination thereof.

**Chain.** Melee Weapon Attack: +7 to hit, reach 15 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, and the target must succeed on a DC 15 Strength saving throw or be pulled into an unoccupied space within 5 feet of the chandelier.

**Lamp.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage plus 13 (3d8) fire damage.

**Blazing Vortex (Recharge 5–6).** Each creature within 20 feet of the chandelier and not behind 3 must succeed on a DC 14 Constitution saving throw or take 36 (8d8) fire damage and have the blinded condition until the start of the chandelier's next turn.


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