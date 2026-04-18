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
  - source/xphb
---
###### Construct Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Construct Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 15 for each spell level above 4 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 18 | 14 | 11 | 5 |
| **Mod** | +4 | +0 | +4 | +2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Understands the languages you know
**Damage Resistances:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Heated Body (Metal Only).** A creature that hits the spirit with a melee attack or that starts its turn in a grapple with the spirit takes 1d10 Fire damage.

**Stony Lethargy (Stone Only).** When a creature starts its turn within 10 feet of the spirit, the spirit can target it with magical energy if the spirit can see it. wis DC equals your spell save DC, the target.  Until the start of its next turn, the target can't make Opportunity Attacks, and its Speed is halved.


---

### Actions

**Multiattack.** The spirit makes a number of Slam attacks equal to half this spell's level (round down).

**Slam.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 4 + summonSpellLevel Bludgeoning damage.


---

### Reactions

**Berserk Lashing (Clay Only).**  The spirit takes damage from a creature.  The spirit makes a Slam attack against that creature if possible, or the spirit moves up to half its Speed toward that creature without provoking Opportunity Attacks.


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