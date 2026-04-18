---
type: pc
race: "Fiend (demon)"
class:
 - "Barlgura"
subClass:
 - "CR 5"
cover: "Barlgura.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/5
  - source/xmm
---
###### Barlgura
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Barlgura.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 7 | 14 | 9 |
| **Mod** | +4 | +2 | +3 | -2 | +2 | -1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 15
**Languages:** Abyssal; telepathy 120 ft.
**Saving Throws:** Dex +5, Con +6
**Skills:** Perception +5, Stealth +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Demonic Restoration.** If the barlgura dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.


---

### Actions

**Multiattack.** The barlgura makes one Tormenting Bite attack and two Thrash attacks.

**Tormenting Bite.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 13 (2d12) Psychic damage.

**Thrash.** m +7, reach 5 ft. *Hit:* 9 (1d10 + 4) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.


---

### Bonus Actions

**Leap.** The barlgura jumps up to 40 feet by spending 10 feet of movement.


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