---
type: pc
race: "Humanoid"
class:
 - "Heralds of Dust Exorcist"
subClass:
 - "CR 6"
cover: "Heralds of Dust Exorcist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/aatm
---
###### Heralds of Dust Exorcist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AATM
___

> [!infobox|no-t right]
> ![[Heralds of Dust Exorcist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | AATM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 16 | 17 | 14 | 11 |
| **Mod** | -1 | +3 | +3 | +3 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 15
**Languages:** Common plus three more languages
**Saving Throws:** Int +6, Wis +5, Cha +3
**Skills:** Arcana +6, Perception +5, Religion +6
**Damage Resistances:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Incorruptible Vessel.** The exorcist can't be possessed by Celestials, Fiends, or Undead.


---

### Actions

**Multiattack.** The exorcist makes two Grave Burst attacks.

**Grave Burst.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 19 (3d10 + 3) necrotic or radiant damage (exorcist's choice).

**Admit Entity (Recharge 5–6).** The exorcist thins the veil of death for a creature it can see within 60 feet of itself, exposing the target to malevolent entities. The target must make a DC 14 Charisma saving throw. On a failed save, the target takes 36 (8d8) psychic damage and has the incapacitated condition for 1 minute, during which time it retches and babbles incoherently in a voice that is not its own. On a successful save, the target takes half as much damage only. An incapacitated target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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