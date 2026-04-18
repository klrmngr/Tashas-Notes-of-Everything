---
type: pc
race: "Giant"
class:
 - "Shadowmoor Giant"
subClass:
 - "CR 8"
cover: "Shadowmoor Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/lfl
---
###### Shadowmoor Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Shadowmoor Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 20 | 7 | 19 | 8 |
| **Mod** | +6 | +2 | +5 | -2 | +4 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Giant
**Saving Throws:** Con +8, Wis +7

---

### Actions

**Multiattack.** The giant makes three attacks, using Tree Club or Boulder in any combination.

**Tree Club.** m +9, reach 15 ft. *Hit:* 17 (2d10 + 6) Bludgeoning damage.

**Boulder.** r +9, range 60/240 ft. *Hit:* 13 (2d6 + 6) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.

**Wild Magic Cataclysm (Recharge 5–6).** dex DC 15, each creature in a 20-foot-radius Sphere centered on a point within 120 feet.  28 (8d6) damage (roll 1d4 to determine damage type: 1—Acid; 2—Fire; 3—Lightning; 4—Thunder).  Half damage.


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