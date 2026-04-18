---
type: pc
race: "Humanoid"
class:
 - "Warlock of the Archfey"
subClass:
 - "CR 4"
cover: "Warlock of the Archfey.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mpmm
---
###### Warlock of the Archfey
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Warlock of the Archfey.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 67 (15d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 11 | 11 | 12 | 18 |
| **Mod** | -1 | +3 | +0 | +0 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any two languages (usually Sylvan)
**Saving Throws:** Wis +3, Cha +6
**Skills:** Arcana +2, Deception +6, Nature +2, Persuasion +6
**Condition Immunities:** charmed

---

### Actions

**Multiattack.** The warlock makes two Rapier attacks, or it uses Bewildering Word twice.

**Rapier.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 7 (2d6) force damage.

**Bewildering Word.** The warlock utters a magical bewilderment, targeting one creature it can see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving throw or take 9 (2d8) psychic damage and have disadvantage on attack rolls until the end of the warlock's next turn.


---

### Reactions

**Misty Escape (Recharges after a Short or Long Rest).** In response to taking damage, the warlock turns invisible and teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see. It remains invisible until the start of its next turn or until it attacks, makes a damage roll, or casts a spell.


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