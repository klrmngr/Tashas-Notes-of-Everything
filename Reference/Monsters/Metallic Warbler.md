---
type: pc
race: "Construct"
class:
 - "Metallic Warbler"
subClass:
 - "CR 1/4"
cover: "Metallic Warbler.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/1-4
  - source/ftd
---
###### Metallic Warbler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Metallic Warbler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 14 (4d4 + 4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 12 | 9 | 10 | 12 |
| **Mod** | -3 | +2 | +1 | -1 | +0 | +1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands Common and Draconic but can't speak
**Saving Throws:** Dex +4
**Damage Immunities:** fire
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The warbler is immune to any spell or effect that would alter its form.

**Telepathic Bond.** While the warbler is on the same plane of existence as its master, it can magically convey what it senses to its master, and the two can communicate telepathically with each other.


---

### Actions

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Calming Mist (Recharge 5–6).** The warbler releases a calming gas in a 5-foot-radius sphere centered on itself. Each creature in that area must succeed on a DC 11 Charisma saving throw or become charmed by the warbler for 1 minute. While charmed in this way, the creature is incapacitated and has a speed of 0.


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