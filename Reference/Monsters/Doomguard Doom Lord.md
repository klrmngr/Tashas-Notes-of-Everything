---
type: pc
race: "Humanoid"
class:
 - "Doomguard Doom Lord"
subClass:
 - "CR 12"
cover: "Doomguard Doom Lord.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/12
  - source/mpp
---
###### Doomguard Doom Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Doomguard Doom Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 202 (27d8 + 81) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 16 | 15 | 14 | 18 |
| **Mod** | +5 | +1 | +3 | +2 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus three more languages
**Saving Throws:** Str +9, Con +7
**Skills:** Perception +6
**Damage Immunities:** necrotic

---

### Traits

**Aura of Doom.** Any creature that starts its turn within 10 feet of the doom lord must make a DC 16 Constitution saving throw, taking 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one. If the doom lord doesn't have the incapacitated condition, it can suppress or resume this aura at the start of its turn (no action required).

**Siege Monster.** The doom lord deals double damage to objects and structures.


---

### Actions

**Multiattack.** The doom lord makes two Entropic Greatsword or Entropic Javelin attacks.

**Entropic Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash.

**Entropic Javelin.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 14 (4d6) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash.


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