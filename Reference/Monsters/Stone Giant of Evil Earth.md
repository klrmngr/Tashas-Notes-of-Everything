---
type: pc
race: "Giant"
class:
 - "Stone Giant of Evil Earth"
subClass:
 - "CR 9"
cover: "Stone Giant of Evil Earth.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/bgg
---
###### Stone Giant of Evil Earth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Stone Giant of Evil Earth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 (plate) |
> | :FasHeart: HP | 137 (11d12 + 66) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 13 | 22 | 10 | 12 | 9 |
| **Mod** | +6 | +1 | +6 | +0 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Giant, Terran
**Saving Throws:** Str +10, Con +10
**Skills:** Athletics +14, Perception +5

---

### Actions

**Multiattack.** The giant makes two Thundering Stone Club or Boulder attacks in any combination.

**Thundering Stone Club.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage. The giant can cause the club to emit a burst of thunderous energy that deals 10 (3d6) thunder damage to each creature, other than the giant, within 30 feet of the target. The club can emit a burst this way only once per turn.

**Boulder.** Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage, and the target must succeed on a DC 18 Strength saving throw or have the prone condition. After the giant throws the boulder, roll a d6; on a roll of 3 or lower, the giant has no more boulders to throw.


---

### Reactions

**Unyielding.** In response to failing a saving throw to avoid being moved, having the prone condition, or both, the giant succeeds instead.


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