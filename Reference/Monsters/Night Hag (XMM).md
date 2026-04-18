---
type: pc
race: "Fiend"
class:
 - "Night Hag"
subClass:
 - "CR 5"
cover: "Night Hag.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/xmm
---
###### Night Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Night Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 16 | 14 | 16 |
| **Mod** | +4 | +2 | +3 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** Abyssal, Common, Infernal, Primordial
**Skills:** Deception +6, Insight +5, Perception +5, Stealth +5
**Damage Resistances:** cold; fire
**Condition Immunities:** charmed

---

### Traits

**Magic Resistance.** The hag has Advantage on saving throws against spells and other magical effects.

**Soul Bag.** The hag has a soul bag. While holding or carrying the bag, the hag can use its Nightmare Haunting action.
The bag has AC 15, HP 20, and Resistance to all damage. The bag turns to dust if reduced to 0 Hit Points. If the bag is destroyed, any souls the bag is holding are released. The hag can create a new bag after 7 days.


---

### Actions

**Multiattack.** The hag makes two Claw attacks.

**Claw.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage.


---

### Bonus Actions

**Shape-Shift.** The hag shape-shifts into a Small or Medium Humanoid, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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