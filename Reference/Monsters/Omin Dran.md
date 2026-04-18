---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Omin Dran"
subClass:
 - "CR 5"
cover: "Omin Dran.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ai
---
###### Omin Dran
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Omin Dran.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 14 | 11 | 18 | 12 |
| **Mod** | +3 | -1 | +2 | +0 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Dwarvish, Elvish, Goblin
**Saving Throws:** Wis +7, Cha +4
**Skills:** Deception +4, Insight +7, Intimidation +4, Medicine +7, Perception +7, Persuasion +4

---

### Traits

**Divine Strike.** Once on each of his turns when he hits a creature with a weapon attack, Omin can cause the attack to deal an extra 4 (1d8) damage of the same type dealt by the weapon.

**Fey Ancestry.** Omin has advantage on saving throws against being charmed, and magic can't put him to sleep.


---

### Actions

**Multiattack.** Omin makes two attacks with his maul.

**Maul.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.


---

### Reactions

**War God's Blessing (Recharges after a Short or Long Rest).** When a creature within 30 feet of Omin makes an attack roll, but before learning whether it hits or misses, Omin can grant the creature a +10 bonus to that roll.


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