---
type: pc
race: "Monstrosity"
class:
 - "Meazel"
subClass:
 - "CR 1"
cover: "Meazel.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/mpmm
---
###### Meazel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Meazel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 35 (10d8 - 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 9 | 14 | 13 | 10 |
| **Mod** | -1 | +3 | -1 | +2 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Common
**Skills:** Perception +3, Stealth +5

---

### Actions

**Garrote.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target of the meazel's size or smaller. *Hit:* 6 (1d6 + 3) bludgeoning damage, and the target is grappled (escape DC 13 with disadvantage). Until the grapple ends, the target takes 10 (2d6 + 3) bludgeoning damage at the start of each of the meazel's turns. The meazel can't make weapon attacks while grappling a creature in this way.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 3 (1d6) necrotic damage.

**Shadow Teleport (Recharge 5–6).** The meazel, any equipment it is wearing or carrying, and any creature it is grappling teleport to an unoccupied space within 500 feet of it, provided that the starting space and the destination are in dim light or darkness. The destination must be a place the meazel has seen before, but it need not be within line of sight. If the destination space is occupied, the teleportation leads to the nearest unoccupied space.
Any other creature the meazel teleports becomes cursed for 1 hour or until the curse is ended by remove curse or greater restoration. Until this curse ends, every Undead and every creature native to the Shadowfell within 300 feet of the cursed creature can sense it, which prevents that creature from hiding from them.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, the meazel takes the Hide action.


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