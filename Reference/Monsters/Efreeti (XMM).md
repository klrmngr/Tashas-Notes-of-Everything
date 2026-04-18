---
type: pc
race: "Elemental (genie)"
class:
 - "Efreeti"
subClass:
 - "CR 11"
cover: "Efreeti.png"
campaign:
locations:
tags:
  - race/genie
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/xmm
---
###### Efreeti
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Efreeti.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental (genie) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 212 (17d10 + 119) |
> | :FasUserGroup: Race | Elemental (genie) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 24 | 16 | 15 | 19 |
| **Mod** | +6 | +1 | +7 | +3 | +2 | +4 |

**Speed:** 40 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Primordial (Ignan)
**Saving Throws:** Wis +6, Cha +8
**Damage Immunities:** fire

---

### Traits

**Elemental Restoration.** If the efreeti dies outside the Elemental Plane of Fire, its body dissolves into ash, and it gains a new body in 1d4 days, reviving with all its Hit Points somewhere on the Plane of Fire.

**Magic Resistance.** The efreeti has Advantage on saving throws against spells and other magical effects.

**Wishes.** The efreeti has a 30 percent chance of knowing the Wish spell. If the efreeti knows it, the efreeti can cast it only on behalf of a non-genie creature who communicates a wish in a way the efreeti can understand. If the efreeti casts the spell for the creature, the efreeti suffers none of the spell's stress. Once the efreeti has cast it three times, the efreeti can't do so again for 365 days.


---

### Actions

**Multiattack.** The efreeti makes three attacks, using Heated Blade or Hurl Flame in any combination.

**Heated Blade.** m +10, reach 5 ft. *Hit:* 13 (2d6 + 6) Slashing damage plus 13 (2d12) Fire damage.

**Hurl Flame.** r +8, range 120 ft. *Hit:* 24 (7d6) Fire damage.


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