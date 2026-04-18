---
type: pc
race: "Construct"
class:
 - "Virvos Magen"
subClass:
 - "CR 6"
cover: "Virvos Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/6
  - source/nf
---
###### Virvos Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Virvos Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 14 | 10 | 10 | 16 |
| **Mod** | +1 | +0 | +2 | +0 | +0 | +3 |

**Speed:** 30 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** understands Common plus two other languages but can't speak
**Skills:** Perception +6
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Disintegration.** If the magen dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The magen makes two Psychic Blast attacks.

**Psychic Blast.** m,r +6, reach 5 ft. or range 60 ft. *Hit:* 21 (6d6) Psychic damage.


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