---
type: pc
race: "Humanoid (druid)"
class:
 - "Firbolg Primeval Warden"
subClass:
 - "CR 4"
cover: "Firbolg Primeval Warden.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/bgg
---
###### Firbolg Primeval Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Firbolg Primeval Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (druid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (hide armor, shield) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (druid) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 12 | 16 | 11 |
| **Mod** | +3 | +2 | +2 | +1 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Druidic, Giant
**Saving Throws:** Int +3, Wis +5
**Skills:** Medicine +5, Nature +3, Perception +7

---

### Actions

**Multiattack.** The firbolg makes two Spear or Fire Lance attacks.

**Spear.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 9 (2d8) fire damage.

**Fire Lance.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 14 (2d10 + 3) fire damage.


---

### Bonus Actions

**Hidden Step (2/Day).** The firbolg magically turns invisible until the start of its next turn, until it makes an attack roll, or until it forces someone to make a saving throw.


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