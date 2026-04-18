---
type: pc
race: "Humanoid"
class:
 - "Mind's Eye Matter Smith"
subClass:
 - "CR 4"
cover: "Mind's Eye Matter Smith.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/mpp
---
###### Mind's Eye Matter Smith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Mind's Eye Matter Smith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 14 | 14 | 16 |
| **Mod** | +0 | +2 | +2 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus two more languages
**Saving Throws:** Int +4, Cha +5
**Skills:** Investigation +4, Perception +6

---

### Actions

**Multiattack.** The matter smith makes two Manifested Force attacks.

**Manifested Force.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 10 (2d6 + 3) force damage.


---

### Bonus Actions

**Planar Smithing.** The matter smith magically manipulates the energy of the plane of existence it's on to produce one of the following effects (choose one or roll a d4):
- **1-2: Chains.** The matter smith creates spectral bindings around a creature it can see within 30 feet of itself. The target must succeed on a DC 13 Dexterity saving throw or have the restrained condition until the end of its next turn.
- **3-4: Magic Shield.** The matter smith conjures a floating, spectral shield that grants the matter smith a +5 bonus to its AC until the shield disappears at the start of the matter smith's next turn. The first time a creature misses a melee attack roll against the matter smith while the shield is conjured, that creature takes 7 (2d6) force damage.


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