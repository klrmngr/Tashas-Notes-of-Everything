---
type: pc
race: "Humanoid"
class:
 - "Fraternity of Order Law Bender"
subClass:
 - "CR 9"
cover: "Fraternity of Order Law Bender.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/9
  - source/mpp
---
###### Fraternity of Order Law Bender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Fraternity of Order Law Bender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 15 | 12 | 19 | 16 | 14 |
| **Mod** | -1 | +2 | +1 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common plus three more languages
**Saving Throws:** Con +5, Wis +7
**Skills:** Insight +7, Perception +7

---

### Actions

**Multiattack.** The law bender makes three Arcane Burst attacks and uses Power of Authority or Spellcasting.

**Arcane Burst.** Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 90 ft., one target. *Hit:* 17 (2d12 + 4) force damage.

**Power of Authority.** The law bender targets a creature it can see within 60 feet of itself. The target must succeed on a DC 16 Intelligence saving throw or take 10 (3d6) psychic damage and have the incapacitated condition for 1 minute. At the end of each of the target's turns, it can repeat the saving throw, ending the incapacitated condition on itself on a success. A target that succeeds on the saving throw becomes immune to this law bender's Power of Authority for 24 hours.


---

### Bonus Actions

**Spatial Loophole.** The law bender teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


---

### Reactions

**Probability Loophole (3/Day).** When the law bender or a creature it can see makes an attack roll, a saving throw, or an ability check, the law bender can cause the roll to be made with advantage or disadvantage.


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