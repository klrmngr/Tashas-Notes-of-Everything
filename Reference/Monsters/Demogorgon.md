---
type: pc
race: "Monstrosity"
class:
 - "Demogorgon"
subClass:
 - "CR 4"
cover: "Demogorgon.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/hftt
---
###### Demogorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HftT
___

> [!infobox|no-t right]
> ![[Demogorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | HftT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 3 | 12 | 5 |
| **Mod** | +3 | +1 | +3 | -4 | +1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +5

---

### Traits

**Keen Smell.** The demogorgon has advantage on Wisdom (Perception) checks that rely on smell.

**Blood Frenzy.** The demogorgon has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Regeneration.** The demogorgon regains 10 hit points at the start of its turn. If the demogorgon takes acid or fire damage, this trait doesn't function at the start of the demogorgon's next turn. The demogorgon dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The demogorgon makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage.


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