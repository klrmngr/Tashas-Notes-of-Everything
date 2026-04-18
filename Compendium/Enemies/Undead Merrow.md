---
type: pc
race: "Undead"
class:
 - "Undead Merrow"
subClass:
 - "CR 3"
cover: "Undead Merrow.png"
campaign: "THE DROWNED CROWN"
locations:
  - "[[Tomb of Sand]]"
tags:
  - race/undead
  - affinity/hostile
  - campaign/theDrownedCrown
---
###### Undead Merrow
:FasPerson: Enemy &nbsp; | &nbsp; :FasMapLocationDot: [[Tomb of Sand]]
___

> [!infobox|no-t right]
> ![[Undead Merrow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Merrow Skeleton |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Undead |

> [!quote|no-t]
> Reanimated merrow corpses raised by [[The Drowned Eternal]]. Drop from the ceiling at the start of **Phase 3**, crashing into the rising water. Stripped of flesh but retaining the bulk and savagery of their living form.

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 15 | 8 | 10 | 9 |
| **Mod** | +4 | +0 | +2 | -1 | +0 | -1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** Poison
**Condition Immunities:** Exhaustion, poisoned

---

### Traits

**Undead Nature.** Doesn't require air, food, drink, or sleep.

**False Appearance.** While motionless underwater, indistinguishable from a waterlogged corpse.

---

### Actions

**Multiattack.** One Bite and one Claws attack, or two Harpoon attacks.

**Bite.** *Melee:* +6 to hit, reach 5 ft. *Hit:* 8 (1d8 + 4) piercing damage.

**Claws.** *Melee:* +6 to hit, reach 5 ft. *Hit:* 11 (2d6 + 4) slashing damage.

**Harpoon.** *Melee or Ranged:* +6 to hit, reach 5 ft. or range 20/60 ft. *Hit:* 11 (2d6 + 4) piercing damage. If the target is a Large or smaller creature, it must succeed on a **DC 14 Strength save** or be pulled up to 20 ft. toward the skeleton.

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
