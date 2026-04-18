---
type: pc
race: "Humanoid (wizard)"
class:
 - "Lorehold Professor of Chaos"
subClass:
 - "CR 7"
cover: "Lorehold Professor of Chaos.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Lorehold Professor of Chaos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Lorehold Professor of Chaos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 19 | 15 | 13 |
| **Mod** | +0 | +2 | +2 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus any four languages
**Saving Throws:** Con +5, Int +7, Wis +5, Cha +4
**Skills:** Arcana +7, History +7, Perception +5

---

### Traits

**Voice from the Past (1/Day).** The professor can cast the contact other plane spell to contact a long-dead spirit, using Intelligence as the spellcasting ability.


---

### Actions

**Multiattack.** The professor makes two Spectral Scroll attacks. It can also use Weight of History, if available.

**Spectral Scroll.** Melee Spell Attack: +7 to hit, reach 30 ft., one target. *Hit:* 15 (2d10 + 4) force damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Weight of History (Recharge 5–6).** The professor magically compresses time around up to six creatures of its choice that it can see within 30 feet of itself. Each target must succeed on a DC 15 Wisdom saving throw or be restrained for 1 minute, but the restrained target's speed is halved instead of being reduced to 0. At the start of each of its turns, the restrained target takes 4 (1d8) force damage. A restrained target can repeat the save at the end of each of its turns, ending the effect on itself on a success.


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