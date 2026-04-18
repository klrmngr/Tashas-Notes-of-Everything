---
type: pc
race: "Humanoid (elf)"
class:
 - "Aerisi Kalinoth"
subClass:
 - "CR 7"
cover: "Aerisi Kalinoth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/pota
---
###### Aerisi Kalinoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Aerisi Kalinoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 17 | 10 | 16 |
| **Mod** | -1 | +3 | +1 | +3 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Auran, Common, Elvish
**Skills:** Arcana +6, History +6, Perception +3
**Damage Resistances:** lightning

---

### Traits

**Fey Ancestry.** Aerisi has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Howling Defeat.** When Aerisi drops to 0 hit points, her body disappears in a howling whirlwind that disperses quickly and harmlessly. Anything she is wearing or carrying is left behind.

**Legendary Resistance (2/Day).** If Aerisi fails a saving throw, she can choose to succeed instead.


---

### Actions

**Windvane.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage, or 10 (1d8 + 6) piercing damage if used with two hands to make a melee attack, plus 3 (1d6) lightning damage.


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