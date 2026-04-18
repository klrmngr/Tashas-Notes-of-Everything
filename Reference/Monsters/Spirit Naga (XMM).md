---
type: pc
race: "Fiend"
class:
 - "Spirit Naga"
subClass:
 - "CR 8"
cover: "Spirit Naga.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/8
  - source/xmm
---
###### Spirit Naga
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spirit Naga.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 17 | 14 | 16 | 15 | 16 |
| **Mod** | +4 | +3 | +2 | +3 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Common
**Saving Throws:** Dex +6, Con +5, Wis +5, Cha +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Fiendish Restoration.** If it dies, the naga returns to life in 1d6 days and regains all its Hit Points. Only a Wish spell can prevent this trait from functioning.


---

### Actions

**Multiattack.** The naga makes three attacks, using Bite or Necrotic Ray in any combination.

**Bite.** m +7, reach 10 ft. *Hit:* 7 (1d6 + 4) Piercing damage plus 14 (4d6) Poison damage.

**Necrotic Ray.** r +6, range 60 ft. *Hit:* 21 (6d6) Necrotic damage.


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