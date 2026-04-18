---
type: pc
race: "Fiend"
class:
 - "Oni"
subClass:
 - "CR 7"
cover: "Oni.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/7
  - source/xmm
---
###### Oni
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Oni.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 16 | 14 | 12 | 15 |
| **Mod** | +4 | +0 | +3 | +2 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common, Giant
**Saving Throws:** Dex +3, Con +6, Wis +4, Cha +5
**Skills:** Arcana +5, Deception +8, Perception +4
**Damage Resistances:** cold

---

### Traits

**Regeneration.** The oni regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.


---

### Actions

**Multiattack.** The oni makes two Claw or Nightmare Ray attacks. It can replace one attack with a use of Spellcasting.

**Claw.** m +7, reach 10 ft. *Hit:* 10 (1d12 + 4) Slashing damage plus 9 (2d8) Necrotic damage.

**Nightmare Ray.** r +5, range 60 ft. *Hit:* 9 (2d6 + 2) Psychic damage, and the target has the Frightened condition until the start of the oni's next turn.

**Shape-Shift.** The oni shape-shifts into a Small or Medium Humanoid or a Large Giant, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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