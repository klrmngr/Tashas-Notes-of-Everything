---
type: pc
race: "Construct"
class:
 - "Minotaur Living Crystal Statue"
subClass:
 - "CR 6"
cover: "Minotaur Living Crystal Statue.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/6
  - source/gos
---
###### Minotaur Living Crystal Statue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Minotaur Living Crystal Statue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 9 | 16 | 6 | 10 | 5 |
| **Mod** | +4 | -1 | +3 | -2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Vulnerabilities:** force
**Damage Immunities:** lightning; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The statue is immune to any spell or effect that would alter its form.


---

### Actions

**Multiattack.** The statue makes two attacks: one with its greataxe and one gore attack.

**Greataxe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 17 (2d12 + 4) slashing damage.

**Gore.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.


---

### Reactions

**Flying Shards.** In response to a creature hitting the statue with a melee weapon attack, the statue deals 11 (2d10) piercing damage to the attacker.


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