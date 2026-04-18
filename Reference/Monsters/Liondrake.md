---
type: pc
race: "Monstrosity"
class:
 - "Liondrake"
subClass:
 - "CR 7"
cover: "Liondrake.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/ftd
---
###### Liondrake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Liondrake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 17 | 6 | 12 | 12 |
| **Mod** | +4 | +2 | +3 | -2 | +1 | +1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Draconic
**Skills:** Perception +7

---

### Actions

**Multiattack.** The liondrake makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Blood-Chilling Roar (Recharge 4–6).** The liondrake lets out a terrifying roar audible out to 300 feet. Any creature within 30 feet of the liondrake that can hear its roar must succeed on a DC 14 Wisdom saving throw or be frightened of the liondrake for 1 minute. A creature that fails the save by 5 or more is also paralyzed for the same duration. A creature can repeat the saving throw at the end of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this liondrake's Blood-Chilling Roar for the next 24 hours.


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