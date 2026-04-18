---
type: pc
race: "Fey"
class:
 - "Naiad"
subClass:
 - "CR 2"
cover: "Naiad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/mot
---
###### Naiad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Naiad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 11 | 15 | 10 | 18 |
| **Mod** | +0 | +3 | +0 | +2 | +0 | +4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Sylvan
**Skills:** Persuasion +6, Sleight Of Hand +5
**Damage Resistances:** psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Amphibious.** The naiad can breathe air and water.

**Invisible in Water.** The naiad is invisible while fully immersed in water.

**Magic Resistance.** The naiad has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The naiad makes two psychic touch attacks.

**Psychic Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) psychic damage.


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