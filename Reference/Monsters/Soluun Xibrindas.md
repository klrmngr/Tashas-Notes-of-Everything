---
type: pc
race: "Humanoid (elf)"
class:
 - "Soluun Xibrindas"
subClass:
 - "CR 4"
cover: "Soluun Xibrindas.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/wdh
---
###### Soluun Xibrindas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Soluun Xibrindas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (studded leather, shield) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 11 | 13 | 14 |
| **Mod** | +1 | +4 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Elvish, Undercommon
**Saving Throws:** Dex +6, Con +4, Wis +3
**Skills:** Perception +3, Stealth +8

---

### Traits

**Fey Ancestry.** Soluun has advantage on saving throws against being charmed, and magic can't put Soluun to sleep.

**Gunslinger.** Being within 5 feet of a hostile creature or attacking at long range doesn't impose disadvantage on Soluun's ranged attack rolls with a pistol. In addition, Soluun ignores 3 and 3 when making ranged attacks with a pistol.

**Sunlight Sensitivity.** While in sunlight, Soluun has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Equipment.** Four packets of smokepowder and a pouch containing 20 pistol bullets

**Boots of Elvenkind.** Whilst wearing these boots Soluun's steps make no sound and he has advantage on any Dexterity (Stealth) checks that rely on moving silently.


---

### Actions

**Multiattack.** Soluun makes two scimitar attacks.

**Scimitar.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Poisonous Pistol.** Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 11 (2d10) poison damage.


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