---
type: pc
race: "Undead"
class:
 - "Brain in a Jar"
subClass:
 - "CR 3"
cover: "Brain in a Jar.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/3
  - source/vrgr
---
###### Brain in a Jar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Brain in a Jar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 55 (10d6 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 3 | 15 | 19 | 10 | 15 |
| **Mod** | -5 | -4 | +2 | +4 | +0 | +2 |

**Speed:** 0 ft., fly 10 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius); see also "detect sentience" below, passive Perception 10
**Languages:** the languages it knew in life
**Saving Throws:** Int +6, Cha +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; poisoned; prone

---

### Traits

**Detect Sentience.** The brain can sense the presence and location of any creature within 300 feet of it that has an Intelligence of 3 or higher, regardless of interposing barriers, unless the creature is protected by a mind blank spell.

**Magic Resistance.** The brain has advantage on saving throws against spells and other magic effects.

**Unusual Nature.** The brain doesn't require air, food, drink, or sleep.


---

### Actions

**Chill Touch (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 13 (3d8) necrotic damage, and the target can't regain hit points until the start of the brain's next turn. If the target is undead, it also has disadvantage on attack rolls against the brain until the end of the brain's next turn.

**Mind Blast (Recharge 5–6).** The brain magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 14 Intelligence saving throw or take 17 (3d8 + 4) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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