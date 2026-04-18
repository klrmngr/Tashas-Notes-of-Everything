---
type: pc
race: "Celestial"
class:
 - "Hound Archon"
subClass:
 - "CR 4"
cover: "Hound Archon.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/4
  - source/mpp
---
###### Hound Archon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Hound Archon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 15 | 11 | 14 | 15 |
| **Mod** | +4 | +1 | +2 | +0 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** all
**Saving Throws:** Int +2, Wis +4
**Skills:** Insight +4, Perception +6, Stealth +3
**Damage Immunities:** lightning
**Condition Immunities:** exhaustion; paralyzed

---

### Traits

**Aura of Menace.** As long as the archon doesn't have the incapacitated condition, each creature of the archon's choice that starts its turn within 20 feet of the archon must make a DC 12 Wisdom saving throw. On a failed save, the creature has the frightened condition until the start of its next turn. On a successful save, the creature is immune to all archons' Aura of Menace for 24 hours.


---

### Actions

**Multiattack.** The archon makes two Bite attacks. It can replace one of the attacks with a Shining Blade attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Strength saving throw or have the prone condition.

**Shining Blade (True Form Only).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) radiant damage.

**Teleport.** The archon teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself.


---

### Bonus Actions

**Change Shape.** The archon magically transforms into any Medium or Large dog or wolf while retaining its game statistics (other than its size and losing its Shining Blade attack). The archon reverts to its true form if reduced to 0 hit points or if it uses a bonus action to do so.


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