---
type: pc
race: "Humanoid (elf)"
class:
 - "Walnut Dankgrass"
subClass:
 - "CR 3"
cover: "Walnut Dankgrass.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/ai
---
###### Walnut Dankgrass
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Walnut Dankgrass.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 14 | 10 | 18 | 10 |
| **Mod** | -1 | +3 | +2 | +0 | +4 | +0 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Druidic, Elvish, Sylvan
**Saving Throws:** Int +2, Wis +6
**Skills:** Athletics +1, Insight +6, Perception +6, Stealth +5, Survival +6

---

### Traits

**Fey Ancestry.** Walnut has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Mask of the Wild.** Walnut can attempt to hide even when she is only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.

**Wild Shape (Recharges after a Short or Long rest).** As a bonus action, Walnut can assume the shape of a dire wolf. She can stay in this form for 3 hours or until she reverts to her normal form as a bonus action. She automatically reverts if she falls unconscious, drops to 0 hit points, or dies.
While transformed, Walnut's game statistics are replaced by the statistics of the dire wolf, except she retains her alignment, personality, and Intelligence, Wisdom, and Charisma scores.
Her attacks in beast form are magical. While in beast form, Walnut can use a bonus action to expend one spell slot and regain 1d8 hit points per level of the spell slot expended.


---

### Actions

**Multiattack.** Walnut makes two attacks with Foremother or her longbow.

**Foremother (+1 Scimitar).** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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