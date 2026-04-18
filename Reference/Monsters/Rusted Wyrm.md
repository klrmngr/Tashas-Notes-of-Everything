---
type: pc
race: "Construct"
class:
 - "Rusted Wyrm"
subClass:
 - "CR 14"
cover: "Rusted Wyrm.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/14
  - source/fraif
---
###### Rusted Wyrm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Rusted Wyrm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 231 (14d20 + 84) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 13 | 22 | 8 | 14 | 6 |
| **Mod** | +7 | +1 | +6 | -1 | +2 | -2 |

**Speed:** 40 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Common, Draconic
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; frightened; petrified; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the Rusted fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The Rusted makes two Bite attacks.

**Bite.** m +12, reach 20 ft. *Hit:* 29 (4d10 + 7) Piercing damage.

**Steam Breath (Recharge 5–6).** dex DC 19, each creature and flammable object that isn't being worn or carried in a 60-foot Cone.  45 (7d12) Fire damage, and the target starts burning.  Half damage only.  Being underwater doesn't grant Resistance to this Fire damage.


---

### Bonus Actions

**Encasing Rust.** con DC 19, one creature within 20 feet of the Rusted.  14 (4d6) Poison damage, and the target has the Poisoned condition until the end of its next turn. While Poisoned, the target has the Paralyzed condition.


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