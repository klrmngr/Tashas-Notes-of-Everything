---
type: pc
race: "Fey (goblinoid)"
class:
 - "Hobgoblin Warlord"
subClass:
 - "CR 6"
cover: "Hobgoblin Warlord.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/6
  - source/xmm
---
###### Hobgoblin Warlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hobgoblin Warlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Fey (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 14 | 11 | 15 |
| **Mod** | +3 | +2 | +3 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin
**Saving Throws:** Dex +5, Int +5, Wis +3, Cha +5

---

### Traits

**Aura of Authority.** While in a 30-foot Emanation originating from the hobgoblin, the hobgoblin and its allies have Advantage on attack rolls and saving throws, provided the hobgoblin doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The hobgoblin makes three attacks, using Javelin or Longsword in any combination.

**Javelin.** m,r +6, reach 5 ft. or range 30/120 ft. *Hit:* 11 (2d6 + 4) Piercing damage, and the target's Speed decreases by 10 feet until the start of the hobgoblin's next turn.

**Longsword.** m +6, reach 5 ft. *Hit:* 12 (2d8 + 3) Slashing damage.


---

### Reactions

**Parry.**  The hobgoblin is hit by a melee attack roll while holding a weapon.  The hobgoblin adds 3 to its AC against that attack, possibly causing it to miss.


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