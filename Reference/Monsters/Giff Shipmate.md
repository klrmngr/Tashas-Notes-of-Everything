---
type: pc
race: "Humanoid"
class:
 - "Giff Shipmate"
subClass:
 - "CR 3"
cover: "Giff Shipmate.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bam
---
###### Giff Shipmate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Giff Shipmate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 11 | 12 | 12 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common

---

### Traits

**Firearms Knowledge.** The giff's mastery of its weapons enables it to ignore the loading property of any firearm.

**Steady as She Goes.** On the deck of a ship, the giff has advantage on ability checks and saving throws made against effects that would knock it prone or shove it overboard.


---

### Actions

**Multiattack.** The giff makes two Longsword or Musket attacks.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Musket.** Ranged Weapon Attack: +4 to hit, range 40/120 ft., one target. *Hit:* 8 (1d12 + 2) piercing damage.

**Force Grenade.** The giff throws a grenade up to 60 feet, and the grenade explodes in a 20-foot-radius sphere. Each creature in that area must make a DC 15 Dexterity saving throw, taking 17 (5d6) force damage on a failed save, or half as much damage on a successful one. After the giff throws the grenade, roll a d6; on a roll of 4 or lower, the giff has no more grenades to throw.


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