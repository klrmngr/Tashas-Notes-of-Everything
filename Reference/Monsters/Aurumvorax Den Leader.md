---
type: pc
race: "Monstrosity"
class:
 - "Aurumvorax Den Leader"
subClass:
 - "CR 4"
cover: "Aurumvorax Den Leader.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/jttrc
---
###### Aurumvorax Den Leader
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Aurumvorax Den Leader.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 3 | 13 | 8 |
| **Mod** | +4 | +2 | +2 | -4 | +1 | -1 |

**Speed:** 40 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Str +6, Con +4
**Skills:** Perception +3, Stealth +4
**Condition Immunities:** petrified

---

### Traits

**Pack Leader.** The aurumvorax's allies have advantage on attack rolls while within 10 feet of the aurumvorax, provided it isn't incapacitated.

**Tunneler.** The aurumvorax can burrow through solid rock and metal at half its burrowing speed and leaves a 5-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The aurumvorax makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage. If the target is a creature wearing armor of any type, the aurumvorax gains one of the following benefits of its choice:

**Frenzy.** The aurumvorax has advantage on attack rolls until start of its next turn.

**Invigorate.** The aurumvorax regains 6 (1d8 + 2) hit points.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage. If the target is a Large or smaller creature, it is grappled (escape DC 14). Until this grapple ends, the aurumvorax can't use its Claw attack on another target, and when it moves, it can drag the grappled creature with it, without the aurumvorax's speed being halved.


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