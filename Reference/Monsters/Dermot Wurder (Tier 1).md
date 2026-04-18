---
type: pc
race: "Humanoid (cleric, goblin, goblinoid)"
class:
 - "Dermot Wurder (Tier 1)"
subClass:
 - "CR 3"
cover: "Dermot Wurder (Tier 1).png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/crcotn
---
###### Dermot Wurder (Tier 1)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Dermot Wurder (Tier 1).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric, goblin, goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (breastplate, shield) |
> | :FasHeart: HP | 44 (8d6 + 16) |
> | :FasUserGroup: Race | Humanoid (cleric, goblin, goblinoid) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 14 | 10 | 16 | 10 |
| **Mod** | +3 | +1 | +2 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Goblin, Orc
**Saving Throws:** Wis +5, Cha +2
**Skills:** Medicine +5, Religion +2, Survival +5

---

### Actions

**Multiattack.** Dermot makes one Warhammer attack and one Searing Wrath attack.

**Warhammer.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage when used with two hands.

**Searing Wrath.** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 9 (2d8) radiant damage, and the target is blinded until the end of its next turn.


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