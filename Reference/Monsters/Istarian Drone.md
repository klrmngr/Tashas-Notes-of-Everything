---
type: pc
race: "Construct"
class:
 - "Istarian Drone"
subClass:
 - "CR 6"
cover: "Istarian Drone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/6
  - source/dsotdq
---
###### Istarian Drone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Istarian Drone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 18 | 4 | 10 | 4 |
| **Mod** | +5 | +0 | +4 | -3 | +0 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** understands the languages spoken by its creator but can't speak
**Damage Immunities:** lightning; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Spider Climb.** The drone can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Unusual Nature.** The drone doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The drone makes two Claw attacks.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage plus 4 (1d8) lightning damage. If the target is a Medium or smaller creature, it is grappled (escape DC 15). The drone has two claws, each of which can grapple only one target.

**Crystalline Spit (Recharge 5–6).** The drone spits crackling gel in a line 5 feet wide and 20 feet long. Each creature in the line must make a DC 15 Dexterity saving throw. On a failed save, the creature takes 14 (4d6) lightning damage and is restrained by the gel, which hardens into crystal. The creature is restrained until the crystal is destroyed. The crystal has AC 15, 15 hit points, immunity to poison and psychic damage, and vulnerability to thunder damage. On a successful save, the creature takes half as much damage and isn't restrained.


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