---
type: pc
race: "Fiend"
class:
 - "Gnoll Demoniac"
subClass:
 - "CR 8"
cover: "Gnoll Demoniac.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/8
  - source/xmm
---
###### Gnoll Demoniac
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gnoll Demoniac.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 14 | 15 | 17 |
| **Mod** | +3 | +1 | +3 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Common, Gnoll
**Saving Throws:** Str +6, Con +6, Wis +5, Cha +6
**Skills:** Perception +5

---

### Actions

**Multiattack.** The gnoll makes two Abyssal Strike attacks.

**Abyssal Strike.** m,r +6, reach 5 ft. or range 60 ft. *Hit:* 20 (5d6 + 3) Poison damage.

**Hunger of Yeenoghu (Recharge 5–6).** The gnoll conjures a 30-foot Cube of magical Darkness originating from a point it can see within 60 feet, which lasts for 1 minute or until the gnoll's Concentration ends on it. This area is Difficult Terrain. dex DC 14, any creature that starts its turn in this area or enters it for the first time on a turn.  28 (8d6) Necrotic damage, and the gnoll or a creature of its choice it can see gains 10 Temporary Hit Points.  Half damage only.


---

### Bonus Actions

**Rampage (2/Day).** Immediately after dealing damage to a creature that is already Bloodied, the gnoll moves up to half its Speed, and it makes one Abyssal Strike attack.


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