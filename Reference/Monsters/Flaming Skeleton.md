---
type: pc
race: "Undead"
class:
 - "Flaming Skeleton"
subClass:
 - "CR 3"
cover: "Flaming Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/xmm
---
###### Flaming Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Flaming Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 15 | 10 | 15 | 8 |
| **Mod** | +0 | +2 | +2 | +0 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands Common plus one other language but can't speak
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The skeleton explodes when it dies. dex DC 12, each creature in a 10-foot Emanation originating from the skeleton.  14 (4d6) Fire damage.  Half damage.

**Illumination.** The skeleton sheds Bright Light in a 15-foot radius and Dim Light for an additional 15 feet.


---

### Actions

**Multiattack.** The skeleton makes two attacks, using Flame Scepter or Hurl Flame in any combination.

**Flame Scepter.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Bludgeoning damage plus 3 (1d6) Fire damage.

**Hurl Flame.** r +4, range 60 ft. *Hit:* 7 (1d10 + 2) Fire damage.


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