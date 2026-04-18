---
type: pc
race: "Plant"
class:
 - "Wolf-in-Sheep's-Clothing"
subClass:
 - "CR 7"
cover: "Wolf-in-Sheep's-Clothing.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/7
  - source/qftis
---
###### Wolf-in-Sheep's-Clothing
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Wolf-in-Sheep's-Clothing.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 9 | 16 | 5 | 12 | 5 |
| **Mod** | +5 | -1 | +3 | -3 | +1 | -3 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** —
**Skills:** Perception +7, Stealth +5
**Condition Immunities:** prone

---

### Traits

**False Appearance.** If the wolf-in-sheep's-clothing is motionless (except for its lure) at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the wolf-in-sheep's-clothing move or act (except for the lure), that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the wolf-in-sheep's-clothing is animate.


---

### Actions

**Multiattack.** The wolf-in-sheep's-clothing makes one Bite attack and two Root Tentacle attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage plus 7 (2d6) acid damage.

**Root Tentacle.** Melee Weapon Attack: +8 to hit, reach 20 ft., one target. *Hit:* 8 (1d6 + 5) bludgeoning damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 16). While grappled in this way, the target has the restrained condition, and at the start of each of the wolf-in-sheep's-clothing's turns, the wolf-in-sheep's-clothing can pull the target up to 10 feet toward itself (no action required). The wolf-in-sheep's-clothing has four root tentacles, each of which can grapple one target.


---

### Bonus Actions

**Completely Harmless Lure.** The wolf-in-sheep's-clothing can change the color, texture, and shape of its lure to resemble a Tiny Beast or Tiny object. It can move the lure to reinforce the resemblance (no action required), but the lure must remain within 15 feet of the wolf-in-sheep's-clothing, connected by nearly invisible filament-like tendrils.


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