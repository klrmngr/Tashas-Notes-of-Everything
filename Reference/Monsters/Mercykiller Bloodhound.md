---
type: pc
race: "Humanoid"
class:
 - "Mercykiller Bloodhound"
subClass:
 - "CR 7"
cover: "Mercykiller Bloodhound.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/mpp
---
###### Mercykiller Bloodhound
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Mercykiller Bloodhound.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 104 (16d8 + 48) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 16 | 12 | 15 | 8 |
| **Mod** | +3 | +1 | +3 | +1 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common plus one more language
**Skills:** Perception +8, Survival +8

---

### Traits

**Portal Sense.** The bloodhound can sense the presence of portals within 30 feet of itself, including inactive portals, and instinctively knows the destination of each portal.


---

### Actions

**Multiattack.** The bloodhound makes three Clawed Gauntlet attacks.

**Clawed Gauntlet.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage plus 10 (3d6) necrotic damage.


---

### Bonus Actions

**Marked for Pursuit (3/Day).** The bloodhound attempts to place a magical mark on a creature it can see within 30 feet of itself. The target must succeed on a DC 13 Charisma saving throw or become cursed for 24 hours. A creature missing any of its hit points has disadvantage on this saving throw. While cursed in this way, the bloodhound can sense the direction and distance to the target as long as the two are on the same plane of existence. If the target isn't on the same plane, the bloodhound knows what plane the target is on.


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