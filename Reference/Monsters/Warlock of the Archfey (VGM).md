---
type: pc
race: "Humanoid (any race)"
class:
 - "Warlock of the Archfey"
subClass:
 - "CR 4"
cover: "Warlock of the Archfey.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/vgm
---
###### Warlock of the Archfey
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Warlock of the Archfey.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 49 (11d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 11 | 11 | 12 | 18 |
| **Mod** | -1 | +1 | +0 | +0 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any two languages (usually Sylvan)
**Saving Throws:** Wis +3, Cha +6
**Skills:** Arcana +2, Deception +6, Nature +2, Persuasion +6
**Condition Immunities:** charmed

---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


---

### Reactions

**Misty Escape (Recharges after a Short or Long Rest).** In response to taking damage, the warlock turns invisible and teleports up to 60 feet to an unoccupied space it can see. It remains invisible until the start of its next turn or until it attacks, makes a damage roll, or casts a spell.


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