---
type: pc
race: "Construct"
class:
 - "Anvilwrought Raptor"
subClass:
 - "CR 1/2"
cover: "Anvilwrought Raptor.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/1-2
  - source/mot
---
###### Anvilwrought Raptor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Anvilwrought Raptor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 18 (4d4 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 3 | 14 | 1 |
| **Mod** | +1 | +3 | +2 | -4 | +2 | -5 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** understands one language of its creator but can't speak
**Skills:** Perception +4
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Keen Sight.** The raptor has advantage on Wisdom (Perception) checks that rely on sight.

**Recorded Mimicry.** The raptor can mimic any sound, including voices, it has heard in the last 24 hours. A creature that hears the sounds can tell they are imitations with a successful DC 12 Wisdom (Insight) check.


---

### Actions

**Multiattack.** The raptor makes two attacks with its beak.

**Beak.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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