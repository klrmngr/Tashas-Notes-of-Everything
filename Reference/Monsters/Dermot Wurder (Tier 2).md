---
type: pc
race: "Humanoid (cleric, goblin, goblinoid)"
class:
 - "Dermot Wurder (Tier 2)"
subClass:
 - "CR 5"
cover: "Dermot Wurder (Tier 2).png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/crcotn
---
###### Dermot Wurder (Tier 2)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Dermot Wurder (Tier 2).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric, goblin, goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (splint mail, shield) |
> | :FasHeart: HP | 82 (15d6 + 30) |
> | :FasUserGroup: Race | Humanoid (cleric, goblin, goblinoid) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 14 | 10 | 18 | 10 |
| **Mod** | +4 | +1 | +2 | +0 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Goblin, Orc
**Saving Throws:** Wis +7, Cha +3
**Skills:** Medicine +7, Religion +3, Survival +7

---

### Actions

**Multiattack.** Dermot makes one Warhammer attack and one Searing Wrath attack.

**Warhammer.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage, or 9 (1d10 + 4) bludgeoning damage when used with two hands.

**Searing Wrath.** Ranged Spell Attack: +7 to hit, range 60 ft., one creature. *Hit:* 18 (4d8) radiant damage, and the target is blinded until the end of its next turn.


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