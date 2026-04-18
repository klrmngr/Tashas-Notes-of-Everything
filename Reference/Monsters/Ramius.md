---
type: pc
race: "Humanoid"
class:
 - "Ramius"
subClass:
 - "CR 14"
cover: "Ramius.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/14
  - source/coa
---
###### Ramius
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Ramius.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 22 (plate, +2 shield) |
> | :FasHeart: HP | 190 (20d8 + 100) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 11 | 14 | 18 |
| **Mod** | +6 | +0 | +5 | +0 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Celestial, Common, Infernal
**Saving Throws:** Wis +7, Cha +9
**Skills:** Animal Handling +12, Athletics +11, Insight +7, Religion +10
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks; 

---

### Traits

**Aura of Protection.** Ramius and any ally that starts their turn within 30 feet of him have a +4 bonus to all saving throws and resistance to nonmagical damage.


---

### Actions

**Multiattack.** Ramius makes two Longsword attacks.

**Longsword.** Melee Weapon Attack: +11 to hit, reach 5ft., one target. *Hit:* 10 (1d8 + 6) slashing damage or 11 (1d10 + 6) if wielded in two hands, plus 13 (3d8) radiant damage. If the target is an evil creature, it must succeed on a DC 17 Charisma saving throw or take an additional 13 (3d8) radiant damage.

**Divine Wave (Recharge 6).** Ramius strikes the ground and causes holy energy to radiate outwards. Each creature of his choice within 30 feet of him must make a DC 17 Constitution saving throw. Targets take 21 (6d6) thunder damage plus 21 (6d6) radiant damage on a failed save, or half as much damage on a successful one. Creatures that fail the save are knocked down (have the prone condition).


---

### Reactions

**Healing Touch.** As a reaction to Ramius or an adjacent creature taking 50 points or more of damage, Ramius reaches out and channels divine energy, healing 13 (2d8 + 4) hit points.


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