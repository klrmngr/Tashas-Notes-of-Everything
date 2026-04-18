---
type: pc
race: "Plant"
class:
 - "Razorvine Blight"
subClass:
 - "CR 1"
cover: "Razorvine Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1
  - source/mpp
---
###### Razorvine Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Razorvine Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 13 | 5 | 10 | 3 |
| **Mod** | +0 | +2 | +1 | -3 | +0 | -4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
**Languages:** understands Common but can't speak
**Skills:** Stealth +4
**Condition Immunities:** blinded; deafened

---

### Traits

**False Appearance.** If the blight is motionless at the start of combat, it has advantage on its initiative roll. If a creature hasn't observed the blight move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the blight is animate.

**Spider Climb.** The blight can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The blight makes two Claw attacks.

**Claw.** Melee Weapon Attack: +4 to hit (with advantage if the target is missing any of its hit points), reach 10 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Life-Draining Vines (Recharge 6).** Snaking vines erupt from the blight. Each creature within 10 feet of it must make a DC 12 Dexterity saving throw, taking 9 (2d8) slashing damage on failed save, or half as much damage on a successful one. If at least one of the creatures that failed this save isn't a Construct or an Undead, the blight regains 9 hit points.


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