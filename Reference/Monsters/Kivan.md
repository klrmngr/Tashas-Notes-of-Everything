---
type: pc
race: "Humanoid (elf)"
class:
 - "Kivan"
subClass:
 - "CR 7"
cover: "Kivan.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/mabjov
---
###### Kivan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Kivan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 132 (24d8 + 24) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 12 | 11 | 14 | 11 |
| **Mod** | +3 | +4 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Dex +7, Wis +5
**Skills:** Nature +6, Perception +8, Stealth +10, Survival +8

---

### Traits

**Fey Ancestry.** Kivan has advantage on saving throws against being charmed, and magic can't put Kivan to sleep.

**Keen Hearing and Sight.** Kivan has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Multiattack.** Kivan makes three Longsword attacks or three Longbow attacks.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage or 8 (1d10 + 3) slashing damage if wielded with two hands.

**Longbow.** Ranged Weapon Attack: +7 to hit, ranged 150/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Volley (2/Day).** Kivan makes a Longbow attack against any number of creatures he can see within 150 feet. He must make a separate attack roll with advantage for each target.


---

### Bonus Actions

**Kivan's Mark.** Kivan designates one creature he can see within 60 feet as his prey. The first time each turn that Kivan hits his prey with a weapon attack, the prey takes an extra 7 (2d6) damage from the weapon.


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