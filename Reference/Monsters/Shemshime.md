---
type: pc
race: "Undead"
class:
 - "Shemshime"
subClass:
 - "CR 4"
cover: "Shemshime.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/cm
---
###### Shemshime
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Shemshime.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 10 | 17 | 14 | 16 |
| **Mod** | -2 | +3 | +0 | +3 | +2 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** telepathy 60 ft.
**Saving Throws:** Int +5, Wis +4
**Skills:** Perception +4, Stealth +7
**Damage Resistances:** acid; bludgeoning; fire; lightning; piercing; slashing; thunder
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Crushing End.** If damage reduces Shemshime to 0 hit points, Shemshime instead drops to 1 hit point unless the damage is the result of Shemshime being crushed by an object weighing at least 1,000 pounds.

**Incorporeal Movement.** Shemshime can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Maddening Touch.** Melee Spell Attack: +5 to hit, reach 5 ft., one target. *Hit:* 17 (4d6 + 3) psychic damage.

**Whispers of Violence.** Shemshime chooses up to two creatures it can see within 60 feet of it. Each target must succeed on a DC 13 Wisdom saving throw, or that target takes 7 (1d8 + 3) psychic damage and must use its reaction to make a melee weapon attack against one creature it can reach (Shemshime's choice) that Shemshime can see.

**Howling Babble (Recharge 6).** Shemshime targets one creature it can see within 30 feet of it. The creature must make a DC 13 Wisdom saving throw. On a failed save, it takes 21 (4d8 + 3) psychic damage and is stunned until the end of its next turn. On a successful save, it takes half as much damage and isn't stunned.


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