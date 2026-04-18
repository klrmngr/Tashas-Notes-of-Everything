---
type: pc
race: "Construct"
class:
 - "Nonaton Modron"
subClass:
 - "CR 10"
cover: "Nonaton Modron.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/10
  - source/mpp
---
###### Nonaton Modron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Nonaton Modron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 161 (19d10 + 57) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 16 | 16 | 13 |
| **Mod** | +4 | +1 | +3 | +3 | +3 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Modron, telepathy 120 ft.
**Saving Throws:** Int +7, Wis +7
**Skills:** Investigation +7, Perception +11

---

### Traits

**Axiomatic Mind.** The nonaton can't be compelled to act in a manner contrary to its nature or its instructions.

**Combat Ready.** The nonaton has advantage on initiative rolls.

**Disintegration.** If the nonaton dies, its body disintegrates into dust, leaving behind anything it was carrying.


---

### Actions

**Multiattack.** The nonaton makes three Arm attacks and uses Pillar of Truth or Spellcasting.

**Arm.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 14). Until this grapple ends, the nonaton can't use this arm against other targets. The nonaton has nine arms, each of which can grapple one target.

**Pillar of Truth.** The nonaton chooses a point on the ground that it can see within 60 feet of itself. A 60-foot-tall, 20-foot-radius cylinder of magical force rises from that point. Each creature in that area must make a DC 15 Dexterity saving throw. On a failed save, a creature takes 21 (6d6) force damage, and the creature reverts to its original form (if it's in a different form) and can't assume a different form until the end of its next turn. On a successful save, a creature takes half as much damage only.


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