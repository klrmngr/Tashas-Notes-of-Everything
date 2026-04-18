---
type: pc
race: "Construct"
class:
 - "Metallic Peacekeeper"
subClass:
 - "CR 4"
cover: "Metallic Peacekeeper.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/ftd
---
###### Metallic Peacekeeper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Metallic Peacekeeper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 68 (8d8 + 32) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 18 | 14 | 12 | 11 |
| **Mod** | +3 | +0 | +4 | +2 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic, telepathy 30 ft.
**Damage Immunities:** fire
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The peacekeeper is immune to any spell or effect that would alter its form.

**Telepathic Bond.** While the peacekeeper is on the same plane of existence as its master, it can magically convey what it senses to its master, and the two can communicate telepathically with each other.


---

### Actions

**Multiattack.** The peacekeeper makes two Slam attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 16 (3d8 + 3) bludgeoning damage.

**Calming Mist (Recharge 5–6).** The peacekeeper releases a calming gas in a 30-foot-radius sphere centered on itself. Each creature in that area must succeed on a DC 14 Charisma saving throw or become charmed by the peacekeeper for 1 minute. While charmed in this way, the creature is incapacitated and has a speed of 0.


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