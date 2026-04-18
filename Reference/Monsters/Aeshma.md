---
type: pc
race: "Humanoid (tiefling)"
class:
 - "Aeshma"
subClass:
 - "CR 2"
cover: "Aeshma.png"
campaign:
locations:
tags:
  - race/tiefling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/coa
---
###### Aeshma
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Aeshma.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (bracers of defense) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (tiefling) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 14 | 14 | 16 |
| **Mod** | +0 | +3 | +2 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Infernal
**Saving Throws:** Dex +5, Cha +5
**Skills:** Deception +7, Insight +4, Performance +7, Persuasion +7, Sleight Of Hand +7, Stealth +5

---

### Actions

**Multiattack.** Aeshma makes two attacks using his Shortsword, Hand Crossbow, or a combination of the two.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Hand Crossbow.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


---

### Bonus Actions

**Cunning.** Aeshma takes the Dash, Disengage, or Hide action.


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