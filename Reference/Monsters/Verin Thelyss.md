---
type: pc
race: "Humanoid (drow, elf)"
class:
 - "Verin Thelyss"
subClass:
 - "CR 5"
cover: "Verin Thelyss.png"
campaign:
locations:
tags:
  - race/drow
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/crcotn
---
###### Verin Thelyss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Verin Thelyss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (drow, elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (drow, elf) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 14 | 13 | 14 | 16 |
| **Mod** | +4 | +2 | +2 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Common, Elvish, Undercommon
**Saving Throws:** Str +7, Con +5, Wis +5
**Skills:** Athletics +7, History +4, Perception +5

---

### Traits

**Fey Ancestry.** Verin has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Sunlight Sensitivity.** While in sunlight, Verin has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Verin makes three Glaive attacks.

**Glaive.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage.

**Hand Crossbow.** Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 22 (4d10) poison damage.


---

### Bonus Actions

**Manifest Echo.** Verin magically creates an echo—a translucent, gray object that looks like him. The echo appears in an unoccupied space Verin can see within 15 feet of himself. While the echo exists, Verin chooses whether each of his attacks originates from his space or the echo's space. On Verin's turn, the echo can move in accordance with Verin's wishes. The echo has AC 17 and 1 hit point. It otherwise uses Verin's statistics. The echo lasts for 1 minute or until it is destroyed, until Verin ends his turn more than 30 feet away from it, until Verin manifests another echo, or until Verin is incapacitated.

**Reposition.** Verin magically swaps places with his echo.


---

### Reactions

**Parry.** Verin adds 3 to his AC against one melee attack that would hit him. To do so, he must see the attacker and be wielding a melee weapon.


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