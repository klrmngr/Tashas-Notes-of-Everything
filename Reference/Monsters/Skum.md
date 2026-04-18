---
type: pc
race: "Aberration"
class:
 - "Skum"
subClass:
 - "CR 5"
cover: "Skum.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/5
  - source/gos
---
###### Skum
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Skum.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 18 | 7 | 12 | 9 |
| **Mod** | +4 | +0 | +4 | -2 | +1 | -1 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Common, Deep Speech, telepathy 60 ft.
**Skills:** Perception +4
**Damage Resistances:** psychic

---

### Traits

**Abolethic Vassal.** The skum is permanently charmed by its aboleth master.

**Amphibious.** The skum can breathe air and water.

**Psychic Conditioning.** The skum is immune to the frightened and charmed conditions unless they are from effects created by an aboleth.

**Water Dependency.** The skum takes 6 (1d12) acid damage every 10 minutes it goes without exposure to water.


---

### Actions

**Multiattack.** The skum makes three attacks: two with its trident and one with its Mind-Breaking Touch.

**Trident.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Mind-Breaking Touch.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 18 (4d8) psychic damage, and the target has disadvantage on Wisdom saving throws until the end of the skum's next turn.


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