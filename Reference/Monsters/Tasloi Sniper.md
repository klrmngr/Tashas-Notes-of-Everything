---
type: pc
race: "Humanoid"
class:
 - "Tasloi Sniper"
subClass:
 - "CR 1"
cover: "Tasloi Sniper.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/mabjov
---
###### Tasloi Sniper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Tasloi Sniper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 21 (6d6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 10 | 12 | 10 | 12 |
| **Mod** | -1 | +4 | +0 | +1 | +0 | +1 |

**Speed:** 25 ft., climb 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Goblin, Sylvan, Tasloi
**Skills:** Stealth +8

---

### Traits

**Javelin Expert.** Tasloi can use their Dexterity for attack and damage rolls with a javelin, just as if the javelin had the finesse property.

**Nimble Escape.** The tasloi can take the Disengage or Hide action as a bonus action on each of its turns.


---

### Actions

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Blowgun.** Ranged Weapon Attack: +6 to hit, range 25/100 ft., one target. *Hit:* 5 (1 + 4) piercing damage and 7 (2d6) poison damage. The target must succeed on a DC 10 Constitution saving throw or have the poisoned condition for 1 hour.

**Javelin.** Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


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