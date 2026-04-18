---
type: pc
race: "Construct"
class:
 - "Terran Magen"
subClass:
 - "CR 8"
cover: "Terran Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/8
  - source/nf
---
###### Terran Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NF
___

> [!infobox|no-t right]
> ![[Terran Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 121 (22d8 + 22) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | NF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 12 | 10 | 18 | 10 |
| **Mod** | +3 | +0 | +1 | +0 | +4 | +0 |

**Speed:** 30 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** understands Common plus two other languages but can't speak
**Saving Throws:** Wis +7
**Skills:** Perception +7
**Damage Immunities:** poison; thunder
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Disintegration.** If the magen dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The magen makes two attacks, using Hammer Fist or Thunderous Boom in any combination.

**Hammer Fist.** m +6, reach 5 ft. *Hit:* 16 (3d8 + 3) Bludgeoning damage plus 13 (3d8) Force damage.

**Thunderous Boom.** r +7, range 60 ft. *Hit:* 28 (8d6) Thunder damage.


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