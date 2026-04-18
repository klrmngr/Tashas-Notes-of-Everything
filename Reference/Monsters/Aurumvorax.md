---
type: pc
race: "Monstrosity"
class:
 - "Aurumvorax"
subClass:
 - "CR 2"
cover: "Aurumvorax.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/2
  - source/jttrc
---
###### Aurumvorax
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Aurumvorax.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 12 | 3 | 12 | 6 |
| **Mod** | +2 | +1 | +1 | -4 | +1 | -2 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Str +4, Con +3
**Skills:** Perception +3, Stealth +3
**Condition Immunities:** petrified

---

### Traits

**Tunneler.** The aurumvorax can burrow through solid rock and metal at half its burrowing speed and leaves a 5-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The aurumvorax makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage. If the target is a creature wearing armor of any type, the aurumvorax regains 4 (1d6 + 1) hit points.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 12). Until this grapple ends, the aurumvorax can't use its Claw attack on another target, and when it moves, it can drag the grappled creature with it, without the aurumvorax's speed being halved.


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