---
type: pc
race: "Monstrosity"
class:
 - "Kalka-Kylla"
subClass:
 - "CR 3"
cover: "Kalka-Kylla.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/tftyp
---
###### Kalka-Kylla
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Kalka-Kylla.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 16 | 15 | 16 | 12 |
| **Mod** | +3 | +1 | +3 | +2 | +3 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 13
**Languages:** Olman
**Skills:** Deception +3, Insight +5, Stealth +3

---

### Traits

**Amphibious.** Kalka-Kylla can breathe air and water.

**False Appearance.** While Kalka-Kylla remains motionless and hidden in its shell, it is indistinguishable from a polished boulder.

**Shell.** Kalka-Kylla can use a bonus action to retract into or emerge from its shell. While retracted, Kalka-Kylla gains a +4 bonus to AC, and it has a speed of 0 and can't benefit from bonuses to speed.


---

### Actions

**Multiattack.** Kalka-Kylla makes two claw attacks.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and if the target is a Medium or smaller creature, it is grappled (escape DC 13). Until this grapple ends, the target is restrained. Kalka-Kylla has two claws, each of which can grapple only one target.


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