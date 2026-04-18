---
type: pc
race: "Monstrosity"
class:
 - "Dragonflesh Grafter"
subClass:
 - "CR 3"
cover: "Dragonflesh Grafter.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/ftd
---
###### Dragonflesh Grafter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragonflesh Grafter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 10 | 10 | 6 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic
**Saving Throws:** Str +5, Con +4

---

### Actions

**Multiattack.** The grafter makes one Claw attack and one Greatclub attack.

**Claw.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage plus 5 (1d10) poison damage.

**Greatclub.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage.

**Acid Retch (Recharge 5–6).** The grafter retches forth a spray of acidic bile in a 30-foot cone. Each creature in that area must make a DC 12 Dexterity saving throw, taking 14 (4d6) acid damage on a failed save, or half as much damage on a successful one.


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