---
type: pc
race: "Monstrosity"
class:
 - "Envy"
subClass:
 - "CR 5"
cover: "Envy.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/wbtw
---
###### Envy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Envy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 18 | 2 | 12 | 7 |
| **Mod** | +5 | +0 | +4 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Sylvan
**Skills:** Perception +4
**Condition Immunities:** petrified

---

### Traits

**Trampling Charge.** If Envy moves at least 20 feet straight toward a creature and then hits it with a bite attack on the same turn, that target must succeed on a DC 16 Strength saving throw or be knocked prone. If the target is prone, Envy can make one attack with its claws against it as a bonus action.


---

### Actions

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 18 (2d12 + 5) piercing damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) bludgeoning damage.

**Petrifying Breath (Recharge 5–6).** Envy exhales petrifying gas in a 30-foot cone. Each creature in that area must succeed on a DC 13 Constitution saving throw. On a failed save, a target begins to turn to stone and is restrained. The restrained target must repeat the saving throw at the end of its next turn. On a success, the effect ends on the target. On a failure, the target is petrified until freed by the greater restoration spell or other magic.


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