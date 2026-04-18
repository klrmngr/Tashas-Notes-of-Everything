---
type: pc
race: "Humanoid"
class:
 - "Giff Shock Trooper"
subClass:
 - "CR 6"
cover: "Giff Shock Trooper.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/bam
---
###### Giff Shock Trooper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Giff Shock Trooper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 11 | 12 | 13 |
| **Mod** | +5 | +2 | +4 | +0 | +1 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common
**Saving Throws:** Str +8, Con +7, Wis +4
**Skills:** Athletics +8, Intimidation +7, Perception +4

---

### Traits

**Firearms Knowledge.** The giff's mastery of its weapons enables it to ignore the loading property of any firearm.

**Headfirst Charge.** If the giff moves at least 20 feet in a straight line and ends within 5 feet of a Large or smaller creature, that creature must succeed on a DC 16 Strength saving throw or take 7 (2d6) bludgeoning damage and be knocked prone.

**Siege Monster.** The giff deals double damage to objects and structures.


---

### Actions

**Multiattack.** The giff makes two Greatsword or Musket attacks.

**Greatsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage.

**Musket.** Ranged Weapon Attack: +5 to hit, range 40/120 ft., one target. *Hit:* 15 (2d12 + 2) piercing damage.

**Thunder Bomb.** The giff lights a grapefruit-sized bomb and throws it at a point up to 60 feet away, where it explodes. Each creature within a 10-foot-radius sphere centered on that point must make a DC 15 Dexterity saving throw, taking 18 (4d8) thunder damage on a failed save, or half as much damage on a successful one. After the giff throws the bomb, roll a d6; on a roll of 4 or lower, the giff has no more bombs to throw.


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