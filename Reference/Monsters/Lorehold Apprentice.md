---
type: pc
race: "Humanoid (wizard)"
class:
 - "Lorehold Apprentice"
subClass:
 - "CR 2"
cover: "Lorehold Apprentice.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/scc
---
###### Lorehold Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Lorehold Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 15 | 12 | 11 |
| **Mod** | +0 | +2 | +1 | +2 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any two languages
**Saving Throws:** Con +3, Int +4
**Skills:** History +6, Insight +3, Investigation +6

---

### Actions

**Scroll Bash.** Melee Spell Attack: +4 to hit, reach 30 ft., one target. *Hit:* 7 (1d10 + 2) bludgeoning damage plus 9 (2d8) thunder damage.

**Reduce to Memory (Recharge 6).** Thundering golden energy erupts around a creature the apprentice can see within 90 feet of it. The creature must make a DC 12 Constitution saving throw, taking 33 (6d10) thunder damage on a failed save, or half as much damage on a successful one. A Construct has disadvantage on the saving throw.


---

### Reactions

**Learn from the Past (2/Day).** When another creature within 60 feet of the apprentice misses a target with an attack roll, the apprentice magically enables the attacker to reroll the attack roll. It must use the new roll.


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