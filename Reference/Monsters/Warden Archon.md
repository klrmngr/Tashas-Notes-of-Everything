---
type: pc
race: "Celestial"
class:
 - "Warden Archon"
subClass:
 - "CR 8"
cover: "Warden Archon.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/8
  - source/mpp
---
###### Warden Archon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Warden Archon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 17 | 15 | 18 | 18 |
| **Mod** | +5 | +0 | +3 | +2 | +4 | +4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 30 ft., passive Perception 20
**Languages:** all
**Saving Throws:** Con +6, Wis +7
**Skills:** Arcana +5, Athletics +8, Perception +10
**Damage Immunities:** lightning
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed

---

### Traits

**Aura of Menace.** As long as the archon doesn't have the incapacitated condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 15 Wisdom saving throw. On a failed save, the creature has the frightened condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.

**Eternal Vigil.** The archon can't be surprised. Moreover, it knows when any creature uses a portal it is assigned to guard.


---

### Actions

**Multiattack.** The archon makes two Claw attacks and one Tracker's Bite attack.

**Claw.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage. If the target is a Medium or smaller creature, the target has the grappled condition (escape DC 18). The archon can have only one creature grappled in this way at a time.

**Tracker's Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) piercing damage. If the target is a creature, for the next 24 hours, the archon knows the distance and direction to the target while they are both on the same plane of existence.

**Teleport.** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.


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