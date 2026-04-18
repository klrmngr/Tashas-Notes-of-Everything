---
type: pc
race: "Construct (dwarf)"
class:
 - "Duergar Screamer"
subClass:
 - "CR 3"
cover: "Duergar Screamer.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/3
  - source/mpmm
---
###### Duergar Screamer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Duergar Screamer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Construct (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Construct (dwarf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 7 | 12 | 5 | 5 | 5 |
| **Mod** | +4 | -2 | +1 | -3 | -3 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 7
**Languages:** understands Dwarvish but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Multiattack.** The screamer makes one Drill attack, and it uses Sonic Scream.

**Drill.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) piercing damage.

**Sonic Scream.** The screamer emits destructive energy in a 15-foot cube. Each creature in that area must succeed on a DC 11 Strength saving throw or take 7 (2d6) thunder damage and be knocked prone.


---

### Reactions

**Engine of Pain.** Immediately after a creature within 5 feet of the screamer hits it with an attack roll, the screamer makes a Drill attack against that creature.


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