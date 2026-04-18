---
type: pc
race: "Giant"
class:
 - "Cloud Giant of Evil Air"
subClass:
 - "CR 12"
cover: "Cloud Giant of Evil Air.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/12
  - source/bgg
---
###### Cloud Giant of Evil Air
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cloud Giant of Evil Air.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 22 | 12 | 16 | 19 |
| **Mod** | +8 | +0 | +6 | +1 | +3 | +4 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Auran, Common, Giant
**Saving Throws:** Con +10, Wis +7, Cha +8
**Skills:** Insight +7, Perception +7, Stealth +4

---

### Traits

**Flyby.** The giant doesn't provoke an opportunity attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The giant makes two Scimitar attacks and one Storm Boomerang attack.

**Scimitar.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 18 (3d6 + 8) slashing damage.

**Storm Boomerang.** Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. *Hit:* 15 (3d4 + 8) bludgeoning damage plus 7 (2d6) thunder damage, and the target must succeed on a DC 16 Constitution saving throw or have the stunned condition until the end of its next turn. The boomerang magically returns to the giant's hand immediately after the attack.


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