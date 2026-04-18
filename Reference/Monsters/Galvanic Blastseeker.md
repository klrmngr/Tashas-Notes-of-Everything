---
type: pc
race: "Humanoid (any race)"
class:
 - "Galvanic Blastseeker"
subClass:
 - "CR 5"
cover: "Galvanic Blastseeker.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ggr
---
###### Galvanic Blastseeker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Galvanic Blastseeker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 14 | 19 | 10 | 13 |
| **Mod** | +0 | +3 | +2 | +4 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common and Primordial, plus any one language
**Saving Throws:** Dex +6
**Skills:** Acrobatics +6, Arcana +7, Perception +3
**Damage Resistances:** lightning; thunder

---

### Traits

**Galvanic Overcast (Recharge 5–6).** When the blastseeker casts lightning bolt or thunderwave, it can roll a die. On an odd number, the blastseeker takes 9 (2d8) force damage. On an even number, the spell also deals 9 (2d8) lightning damage to each target that fails its saving throw.

**Heart of the Storm.** When the blastseeker casts lightning bolt or thunderwave, all other creatures within 10 feet of the blastseeker each take 3 lightning damage.

**Gust-Propelled Leap.** The blastseeker can use a bonus action to fly up to 10 feet without provoking opportunity attacks.


---

### Actions

**Spear.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d6) piercing damage, or 4 (1d8) piercing damage if used with two hands to make a melee attack.


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