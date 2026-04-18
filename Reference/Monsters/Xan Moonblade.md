---
type: pc
race: "Humanoid (elf)"
class:
 - "Xan Moonblade"
subClass:
 - "CR 8"
cover: "Xan Moonblade.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mabjov
---
###### Xan Moonblade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Xan Moonblade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 112 (25d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 11 | 17 | 12 | 11 |
| **Mod** | +0 | +3 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Elvish
**Saving Throws:** Int +6, Wis +4
**Skills:** Acrobatics +9, Arcana +6, History +6, Performance +6

---

### Traits

**Enchanter.** When Xan casts hideous laughter, hold person, or suggestion, the target has disadvantage on the saving throw.

**Fey Ancestry.** Xan has advantage on saving throws against being charmed, and magic can't put Xan to sleep.

**Special Equipment.** Xan wields a Moonblade. The Moonblade has a +3 bonus to attack and damage rolls (already factored into Xan's attacks) and has the finesse property.


---

### Actions

**Multiattack.** Xan makes three Moonblade attacks.

**Moonblade.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) slashing damage or 11 (1d10 + 6) slashing damage if wielded with two hands, plus 7 (2d6) cold or fire damage (Xan's choice).


---

### Bonus Actions

**Bladesong (1/Day).** Xan can use a bonus action to start a bladesong. His bladesong lasts for 1 minute. While using bladesong his movement increases to 40 ft., he gains a +3 bonus to his AC and he gains a +3 bonus to all concentration checks.


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