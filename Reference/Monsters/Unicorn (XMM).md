---
type: pc
race: "Celestial"
class:
 - "Unicorn"
subClass:
 - "CR 5"
cover: "Unicorn.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/5
  - source/xmm
---
###### Unicorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Unicorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 97 (13d10 + 26) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 17 | 16 |
| **Mod** | +4 | +2 | +2 | +0 | +3 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Celestial, Elvish, Sylvan; telepathy 120 ft.
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the unicorn fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The unicorn has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The unicorn makes one Hooves attack and one Radiant Horn attack.

**Hooves.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Bludgeoning damage.

**Radiant Horn.** m +7, reach 5 ft. *Hit:* 9 (1d10 + 4) Radiant damage.


---

### Legendary Actions

### 

**Charging Horn.** The unicorn moves up to half its Speed without provoking Opportunity Attacks, and it makes one Radiant Horn attack.

**Shimmering Shield.** The unicorn targets itself or one creature it can see within 60 feet of itself. The target gains 10 (3d6) Temporary Hit Points, and its AC increases by 2 until the end of the unicorn's next turn. The unicorn can't take this action again until the start of its next turn.


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