---
type: pc
race: "Monstrosity"
class:
 - "Thanoi Hunter"
subClass:
 - "CR 1"
cover: "Thanoi Hunter.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/mcv2dc
---
###### Thanoi Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Thanoi Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 12 | 16 | 11 |
| **Mod** | +4 | +2 | +2 | +1 | +3 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Aquan, Common
**Saving Throws:** Str +6, Con +4
**Skills:** Athletics +6, Perception +5, Survival +5
**Damage Immunities:** cold

---

### Traits

**Hold Breath.** The hunter can hold its breath for up to 10 minutes.

**Pack Tactics.** The hunter has advantage on an attack roll against a creature if at least one of the hunter's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The hunter makes one Bone Harpoon attack and one Tusk attack.

**Bone Harpoon.** Melee or Ranged Weapon Attack: +6 to hit, reach 10 ft. or range 20/60 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage. The harpoon returns to the hunter's hand.

**Tusk.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage.


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