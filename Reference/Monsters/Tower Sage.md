---
type: pc
race: "Humanoid"
class:
 - "Tower Sage"
subClass:
 - "CR 1"
cover: "Tower Sage.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/qftis
---
###### Tower Sage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Tower Sage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 16 | 14 | 16 |
| **Mod** | +0 | +0 | +0 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any three languages
**Skills:** Arcana +5, History +5, Insight +4

---

### Actions

**Multiattack.** The tower sage makes two Arcane Burst attacks and can use Starry Radiance if available.

**Arcane Burst.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 8 (1d10 + 3) radiant damage.

**Starry Radiance (Recharge 5–6).** Dazzling light bursts from the tower sage's fingertips in a 15-foot cone. Each creature in that area must succeed on a DC 13 Constitution saving throw or have the blinded condition until the end of the tower sage's next turn.


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