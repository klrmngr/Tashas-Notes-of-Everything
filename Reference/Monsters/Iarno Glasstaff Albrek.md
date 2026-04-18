---
type: pc
race: "Humanoid (human, wizard)"
class:
 - "Iarno "Glasstaff" Albrek"
subClass:
 - "CR 1"
cover: "Iarno "Glasstaff" Albrek.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/pabtso
---
###### Iarno "Glasstaff" Albrek
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Iarno "Glasstaff" Albrek.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 16 with mage armor and staff of defense |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (human, wizard) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Elvish
**Saving Throws:** Int +5, Wis +3
**Skills:** Arcana +5, History +5

---

### Traits

**Special Equipment.** Glasstaff wields a staff of defense (see appendix B). With the staff in hand, he can use an action to cast the mage armor spell and use his reaction to cast the shield spell.


---

### Actions

**Multiattack.** Glasstaff makes two Shocking Burst attacks.

**Shocking Burst.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 6 (1d6 + 3) lightning damage.


---

### Bonus Actions

**Teleport (2/Day).** Glasstaff magically teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see.


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