---
type: pc
race: "Giant"
class:
 - "B'rohg"
subClass:
 - "CR 6"
cover: "B'rohg.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/bam
---
###### B'rohg
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[B'rohg.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 92 (8d12 + 40) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 21 | 5 | 10 | 7 |
| **Mod** | +5 | +2 | +5 | -3 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Skills:** Athletics +8, Survival +6

---

### Actions

**Multiattack.** The b'rohg makes four Fist attacks or two Rock attacks.

**Fist.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +5 to hit, range 60/240 ft., one target. *Hit:* 23 (4d8 + 5) bludgeoning damage.

**Hideous Rend.** The b'rohg uses all four of its hands to target one Large or smaller creature it can see within 10 feet of itself. The target must succeed on a DC 16 Dexterity saving throw or be grappled (escape DC 16). Until this grapple ends, the b'rohg can't make Fist attacks or Rock attacks, and the target takes 49 (8d10 + 5) bludgeoning damage at the start of each of its turns. A creature reduced to 0 hit points by this damage is ripped into four pieces.


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