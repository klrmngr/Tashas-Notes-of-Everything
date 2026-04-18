---
type: pc
race: "Fey"
class:
 - "Annis Hag"
subClass:
 - "CR 6"
cover: "Annis Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/6
  - source/vgm
---
###### Annis Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Annis Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 14 | 13 | 14 | 15 |
| **Mod** | +5 | +1 | +2 | +1 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Giant, Sylvan
**Saving Throws:** Con +5
**Skills:** Deception +5, Perception +5
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks

---

### Actions

**Multiattack.** The annis makes three attacks: one with her bite and two with her claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) piercing damage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage.

**Crushing Hug.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 36 (9d6 + 5) bludgeoning damage, and the target is grappled (escape DC 15) if it is a Large or smaller creature. Until the grapple ends, the target takes 36 (9d6 + 5) bludgeoning damage at the start of each of the hag's turns. The hag can't make attacks while grappling a creature in this way.


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