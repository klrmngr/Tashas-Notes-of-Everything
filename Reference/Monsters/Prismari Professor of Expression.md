---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Prismari Professor of Expression"
subClass:
 - "CR 7"
cover: "Prismari Professor of Expression.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Prismari Professor of Expression
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Prismari Professor of Expression.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 15 | 15 | 13 | 19 |
| **Mod** | +2 | +3 | +2 | +2 | +1 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus any four languages
**Saving Throws:** Dex +6, Int +5, Wis +4, Cha +7
**Skills:** Acrobatics +6, Arcana +5, Athletics +5, Perception +4, Performance +10
**Damage Resistances:** fire; lightning

---

### Actions

**Multiattack.** The professor makes three Cinder Strike attacks.

**Cinder Strike.** Melee Spell Attack: +7 to hit, reach 15 ft., one target. *Hit:* 13 (2d8 + 4) fire damage.

**Lightning Flourish (Recharge 6).** The professor unleashes arcs of magical lightning at up to two creatures it can see within 60 feet of itself. Each target must make a DC 15 Dexterity saving throw, taking 35 (10d6) lightning damage on a failed save, or half as much damage on a successful one.


---

### Bonus Actions

**Flaming Leap.** The professor is wreathed in flames and jumps up to 30 feet in any direction. When the professor lands, the flames erupt in a 10-foot radius around the professor and then vanish. Each creature of the professor's choice in that area must succeed on a DC 15 Dexterity saving throw or take 7 (2d6) fire damage.


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