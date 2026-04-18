---
type: pc
race: "Aberration"
class:
 - "Nothic"
subClass:
 - "CR 2"
cover: "Nothic.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/mm
---
###### Nothic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Nothic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 16 | 13 | 10 | 8 |
| **Mod** | +2 | +3 | +3 | +1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 12
**Languages:** Undercommon
**Skills:** Arcana +3, Insight +4, Perception +2, Stealth +5

---

### Traits

**Keen Sight.** The nothic has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The nothic makes two claw attacks.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Rotting Gaze.** The nothic targets one creature it can see within 30 feet of it. The target must succeed on a DC 12 Constitution saving throw against this magic or take 10 (3d6) necrotic damage.

**Weird Insight.** The nothic targets one creature it can see within 30 feet of it. The target must contest its Charisma (Deception) check against the nothic's Wisdom (Insight) check. If the nothic wins, it magically learns one fact or secret about the target. The target automatically wins if it is immune to being charmed.


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