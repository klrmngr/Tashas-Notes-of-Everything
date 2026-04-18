---
type: pc
race: "Aberration"
class:
 - "Phaerimm Scout"
subClass:
 - "CR 2"
cover: "Phaerimm Scout.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/nf
---
###### Phaerimm Scout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Phaerimm Scout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 12 | 15 | 16 | 16 |
| **Mod** | +1 | +1 | +1 | +2 | +3 | +3 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 15
**Languages:** telepathy 120 ft. understands Common and Deep Speech but can't speak
**Saving Throws:** Int +4, Cha +5
**Skills:** Perception +5
**Condition Immunities:** charmed

---

### Traits

**Magic Resistance.** The phaerimm has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The phaerimm makes two attacks, using Stinger or Mindwarp Ray in any combination.

**Stinger.** m +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Piercing damage plus 9 (2d8) Poison damage.

**Mindwarp Ray.** r +5, range 120 ft. *Hit:* 6 (1d6 + 3) Psychic damage, and the target has the Charmed condition until the start of the phaerimm's next turn.


---

### Reactions

**Uncanny Dodge.**  The phaerimm is hit by an attack roll.  The phaerimm halves the damage (round down) it takes from that attack.


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