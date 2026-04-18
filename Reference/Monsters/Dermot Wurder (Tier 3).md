---
type: pc
race: "Humanoid (cleric, goblin, goblinoid)"
class:
 - "Dermot Wurder (Tier 3)"
subClass:
 - "CR 8"
cover: "Dermot Wurder (Tier 3).png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/crcotn
---
###### Dermot Wurder (Tier 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Dermot Wurder (Tier 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric, goblin, goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 20 (plate, shield) |
> | :FasHeart: HP | 93 (17d6 + 34) |
> | :FasUserGroup: Race | Humanoid (cleric, goblin, goblinoid) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 14 | 10 | 20 | 10 |
| **Mod** | +4 | +1 | +2 | +0 | +5 | +0 |

**Speed:** 30 ft., swim 30 ft. ((mariner's armor)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Goblin, Orc
**Saving Throws:** Wis +8, Cha +3
**Skills:** Medicine +8, Religion +3, Survival +8

---

### Traits

**Special Equipment.** Dermot wears mariner's armor and wields a ruidium warhammer (see appendix B). If Dermot rolls a 1 on an attack roll made with the warhammer, he must succeed on a DC 20 Charisma saving throw or gain 1 level of exhaustion.


---

### Actions

**Multiattack.** Dermot makes one Ruidium Warhammer attack and one Searing Wrath attack.

**Ruidium Warhammer.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage, or 9 (1d10 + 4) bludgeoning damage when used with two hands, plus 7 (2d6) psychic damage.

**Searing Wrath.** Ranged Spell Attack: +8 to hit, range 60 ft., one creature. *Hit:* 22 (5d8) radiant damage, and the target is blinded until the end of its next turn.


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