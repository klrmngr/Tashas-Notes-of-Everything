---
type: pc
race: "Undead"
class:
 - "Brain in a Jar"
subClass:
 - "CR 6"
cover: "Brain in a Jar.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/llk
---
###### Brain in a Jar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Laboratory of Kwalish
___

> [!infobox|no-t right]
> ![[Brain in a Jar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Lost Laboratory of Kwalish |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 1 | 15 | 19 | 10 | 15 |
| **Mod** | -5 | -5 | +2 | +4 | +0 | +2 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +7, Cha +5
**Damage Immunities:** necrotic; poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Detect Sentience.** The brain in a jar can sense the presence and location of any creature within 300 feet of it that has an Intelligence of 3 or higher, regardless of interposing barriers, unless the creature is protected by a mind blank spell.

**Magic Resistance.** The brain in a jar has advantage on saving throws against spells and other magical effects.


---

### Actions

**Mind Blast (Recharge 5–6).** The brain in a jar magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take 13 (2d8 + 4) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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