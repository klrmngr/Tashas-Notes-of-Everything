---
type: pc
race: "Construct"
class:
 - "Squirt the Oilcan"
subClass:
 - "CR 1/4"
cover: "Squirt the Oilcan.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/1-4
  - source/wbtw
---
###### Squirt the Oilcan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Squirt the Oilcan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 17 (7d4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 15 | 10 | 11 | 8 | 15 |
| **Mod** | -4 | +2 | +0 | +0 | -1 | +2 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Common, Dwarvish, Sylvan
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; poisoned; unconscious

---

### Traits

**False Appearance.** If Squirt is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed Squirt move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that Squirt is animate.

**Unusual Nature.** Squirt doesn't require air, food, drink, or sleep.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Boggle Oil (3 Applications).** Squirt expends 1 application of boggle oil to create a 10-foot-square puddle of slippery, non-flammable oil on the ground within 5 feet of it. The puddle is 3 and lasts for 1 hour. Each creature that enters the puddle's area or starts its turn there must succeed on a DC 11 Dexterity saving throw or fall prone. Boggles are unaffected by the oil. After it expends all 3 applications, Squirt can't use this action again until its supply of boggle oil is replenished.


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