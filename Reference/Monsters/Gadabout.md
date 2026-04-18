---
type: pc
race: "Plant"
class:
 - "Gadabout"
subClass:
 - "CR 1/8"
cover: "Gadabout.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-8
  - source/mcv1sc
---
###### Gadabout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Gadabout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 14 | 1 | 6 | 1 |
| **Mod** | +1 | +0 | +2 | -5 | -2 | -5 |

**Speed:** 10 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 10 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Damage Vulnerabilities:** fire
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified

---

### Traits

**Air Envelope.** If it has at least 1 hit point, the gadabout can generate an air envelope around itself when in a vacuum. This air envelope can sustain the gadabout and one other creature in its space indefinitely.

**Unusual Nature.** The gadabout doesn't require food or sleep.


---

### Actions

**Multiattack.** The gadabout makes two Branch attacks.

**Branch.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) slashing damage.

**Wrap.** The gadabout enters the space of a willing Medium or Small creature within 5 feet of itself and gently wraps its branches around the target. The target is grappled (escape DC 0). Any attempt by the target to escape the grapple causes the gadabout to use its reaction to move into the nearest unoccupied space. While grappled by the gadabout, the target determines where the gadabout moves on the gadabout's turns and accompanies the gadabout wherever it goes.


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