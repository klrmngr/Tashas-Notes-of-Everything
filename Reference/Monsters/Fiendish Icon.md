---
type: pc
race: "Construct"
class:
 - "Fiendish Icon"
subClass:
 - "CR 1"
cover: "Fiendish Icon.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1
  - source/abh
---
###### Fiendish Icon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ABH
___

> [!infobox|no-t right]
> ![[Fiendish Icon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | ABH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 13 | 6 | 11 | 6 |
| **Mod** | +2 | +1 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60, passive Perception 10
**Languages:** understands Common and Infernal but can't speak
**Skills:** Stealth +5
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The icon has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The icon makes two Slam attacks and uses Fiery Eruption.

**Slam.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Bludgeoning damage.

**Fiery Eruption.** dex DC 11, each creature in a 5-foot Emanation originating from the icon.  7 (2d6) Fire damage.


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