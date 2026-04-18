---
type: pc
race: "Humanoid (human)"
class:
 - "Manshoon"
subClass:
 - "CR 13"
cover: "Manshoon.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/wdh
---
###### Manshoon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Manshoon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (robe of the archmagi, staff of power) |
> | :FasHeart: HP | 126 (23d8 + 23) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 23 | 15 | 16 |
| **Mod** | +0 | +2 | +1 | +6 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic, Goblin, Infernal, Orc, Undercommon
**Saving Throws:** Str +2, Dex +4, Con +3, Int +13, Wis +9, Cha +5
**Skills:** Arcana +11, History +11

---

### Traits

**Special Equipment.** Manshoon wears a black robe of the archmagi and wields a staff of power (both accounted for in his statistics). Roll 2d10 to determine how many charges the staff has remaining.

**Magic Resistance.** While wearing his robe of the archmagi, Manshoon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Metal Fist.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Staff of Power.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage when used with two hands. Manshoon can expend 1 of the staff's charges to deal an extra 3 (1d6) force damage on a hit.


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