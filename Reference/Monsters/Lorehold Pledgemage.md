---
type: pc
race: "Humanoid (wizard)"
class:
 - "Lorehold Pledgemage"
subClass:
 - "CR 4"
cover: "Lorehold Pledgemage.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/scc
---
###### Lorehold Pledgemage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Lorehold Pledgemage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 13 | 17 | 12 | 11 |
| **Mod** | +0 | +3 | +1 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any two languages
**Saving Throws:** Con +3, Int +5
**Skills:** History +7, Insight +3, Investigation +7

---

### Actions

**Multiattack.** The pledgemage makes two Scroll Bash attacks.

**Scroll Bash.** Melee Spell Attack: +5 to hit, reach 30 ft., one target. *Hit:* 8 (1d10 + 3) bludgeoning damage plus 9 (2d8) thunder damage.

**Reduce to Memory (Recharge 5–6).** Thundering golden energy erupts around a creature the pledgemage can see within 90 feet of it. The creature must make a DC 13 Constitution saving throw, taking 44 (8d10) thunder damage on a failed save, or half as much damage on a successful one. A Construct has disadvantage on the saving throw.


---

### Bonus Actions

**Chronal Break (1/Day).** The pledgemage chooses a point within 30 feet of itself, shunting the minds of nearby creatures out of this moment in time. Each creature in a 10-foot-radius sphere centered on that point must succeed on a DC 13 Wisdom saving throw or be incapacitated until the end of the pledgemage's next turn.


---

### Reactions

**Learn from the Past (2/Day).** When another creature within 60 feet of the pledgemage misses a target with an attack roll, the pledgemage magically enables the attacker to reroll the attack roll. It must use the new roll.


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