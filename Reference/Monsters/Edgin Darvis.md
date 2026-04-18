---
type: pc
race: "Humanoid (bard)"
class:
 - "Edgin Darvis"
subClass:
 - "CR 5"
cover: "Edgin Darvis.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hat-tg
---
###### Edgin Darvis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Edgin Darvis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (bard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid (bard) |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 14 | 16 | 18 |
| **Mod** | +2 | +3 | +2 | +2 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Saving Throws:** Dex +6, Cha +7
**Skills:** Deception +7, Performance +10, Persuasion +10, Sleight Of Hand +6

---

### Actions

**Multiattack.** Edgin makes two Reinforced Lute or Shortsword attacks.

**Reinforced Lute.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage plus 11 (2d10) thunder damage.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 11 (2d10) thunder damage.

**Disorienting Words.** Edgin magically taunts up to three creatures he can see within 60 feet of himself. Each creature must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage and have disadvantage on the next attack roll it makes before the start of Edgin's next turn.


---

### Reactions

**Inspiring Words (3/Day).** When a creature Edgin can see within 60 feet of himself fails an ability check, an attack roll, or a saving throw, Edgin grants the creature magical encouragement. The creature can roll a d8 and add the number rolled to the total, potentially turning the failure into a success.


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