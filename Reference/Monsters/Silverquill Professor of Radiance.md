---
type: pc
race: "Humanoid (bard)"
class:
 - "Silverquill Professor of Radiance"
subClass:
 - "CR 7"
cover: "Silverquill Professor of Radiance.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Silverquill Professor of Radiance
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Silverquill Professor of Radiance.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (bard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (bard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 16 | 13 | 19 |
| **Mod** | +0 | +2 | +2 | +3 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any four languages
**Saving Throws:** Dex +5, Int +6, Wis +4, Cha +7
**Skills:** Arcana +6, Deception +7, Performance +10, Persuasion +10
**Damage Resistances:** radiant

---

### Actions

**Multiattack.** The professor makes two Radiant Strike attacks. The professor can replace one of the attacks with a use of Spellcasting.

**Radiant Strike.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 17 (3d8 + 4) radiant damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw be blinded until the end of its next turn.


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