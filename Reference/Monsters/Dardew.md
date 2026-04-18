---
type: pc
race: "Fiend"
class:
 - "Dardew"
subClass:
 - "CR 5"
cover: "Dardew.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/wtthc
---
###### Dardew
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Dardew.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 16 | 14 | 12 | 16 |
| **Mod** | +4 | +4 | +3 | +2 | +1 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Int +5, Cha +6
**Skills:** Deception +6, Perception +4, Performance +9
**Damage Resistances:** cold; fire; lightning; poison
**Condition Immunities:** poisoned

---

### Actions

**Multiattack.** Dardew makes two attacks, using Fiery Claw or Power Chord in any combination.

**Fiery Claw.** m +7, reach 5 ft.  *Hit:* 8 (1d8 + 4) Slashing damage plus 7 (2d6) Fire damage.

**Power Chord.** con DC 14, one creature Dardew can see within 120 ft.  13 (3d6 + 3) Thunder damage.


---

### Bonus Actions

**Silver Tongue.** cha DC 14, one creature Dardew can see within 60 feet.  The creature has the Charmed condition until the start of Dardew's next turn.


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