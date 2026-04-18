---
type: pc
race: "Fey"
class:
 - "Giant Goose"
subClass:
 - "CR 3"
cover: "Giant Goose.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/3
  - source/bgg
---
###### Giant Goose
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Giant Goose.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 15 | 6 | 14 | 11 |
| **Mod** | +2 | +3 | +2 | -2 | +2 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands Giant and Sylvan but can't speak
**Skills:** Perception +6

---

### Actions

**Multiattack.** The goose makes one Beak attack and two Wing attacks.

**Beak.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage.

**Wing.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) bludgeoning damage, and the target must succeed on a DC 12 Strength saving throw or have the prone condition.

**Thunderous Honk (Recharge 5–6).** The goose honks with ear-splitting volume. Each other creature within 30 feet of the goose must make a DC 12 Constitution saving throw. On a failed save, a creature takes 16 (3d10) thunder damage and has the deafened condition until the start of the goose's next turn. On a successful save, a creature takes half as much damage only. The honk can be heard within 300 feet.


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