---
type: pc
race: "Humanoid (druid)"
class:
 - "Witherbloom Professor of Growth"
subClass:
 - "CR 7"
cover: "Witherbloom Professor of Growth.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Witherbloom Professor of Growth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Witherbloom Professor of Growth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (druid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 16 | 16 | 19 | 13 |
| **Mod** | +0 | +1 | +3 | +3 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus any four languages
**Saving Throws:** Con +6, Int +6, Wis +7, Cha +4
**Skills:** Arcana +6, Medicine +7, Nature +6, Survival +7
**Damage Resistances:** poison
**Condition Immunities:** poisoned

---

### Actions

**Multiattack.** The professor makes two Verdant Lash attacks.

**Verdant Lash.** Melee Spell Attack: +7 to hit, reach 30 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage plus 7 (2d6) poison damage, and the target must succeed on a DC 15 Strength saving throw or be pulled up to 10 feet closer to the professor.

**Summon Nature's Avatar (Recharges after a Short or Long Rest).** The professor magically summons a Groff. The groff appears in an unoccupied space within 60 feet of the professor, acts as the professor's ally, and takes its turns immediately after the professor's. The professor can communicate telepathically with this groff while it remains. The groff remains for 10 minutes, until it or the professor dies, or until the professor dismisses it as an action.


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