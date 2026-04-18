---
type: pc
race: "Construct"
class:
 - "Construct Spirit"
subClass:
 - "CR —"
cover: "Construct Spirit.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/tce
---
###### Construct Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Construct Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 15 for each spell level above 4th |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 14 | 11 | 5 |
| **Mod** | +4 | +0 | +4 | +2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages you speak
**Damage Resistances:** poison
**Condition Immunities:** charmed; exhaustion; frightened; incapacitated; paralyzed; petrified; poisoned

---

### Traits

**Heated Body (Metal Only).** A creature that touches the construct or hits it with a melee attack while within 5 feet of it takes 1d10 fire damage.

**Stony Lethargy (Stone Only).** When a creature the construct can see starts its turn within 10 feet of the construct, the construct can force it to make a Wisdom saving throw against your spell save DC. On a failed save, the target can't use reactions and its speed is halved until the start of its next turn.


---

### Actions

**Multiattack.** The construct makes a number of attacks equal to half this spell's level (rounded down).

**Slam.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d8 + 4 + summonSpellLevel bludgeoning damage.


---

### Reactions

**Berserk Lashing (Clay Only).** When the construct takes damage, it makes a slam attack against a random creature within 5 feet of it. If no creature is within reach, the construct moves up to half its speed toward an enemy it can see, without provoking opportunity attacks.


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