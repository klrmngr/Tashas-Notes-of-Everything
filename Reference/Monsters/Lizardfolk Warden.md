---
type: pc
race: "Elemental"
class:
 - "Lizardfolk Warden"
subClass:
 - "CR 1"
cover: "Lizardfolk Warden.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/1
  - source/hotb
---
###### Lizardfolk Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Lizardfolk Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 14 | 10 | 12 | 8 |
| **Mod** | +2 | +1 | +2 | +0 | +1 | -1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic
**Skills:** Stealth +5, Survival +5

---

### Traits

**Hold Breath.** The lizardfolk can hold its breath for 15 minutes.


---

### Actions

**Multiattack.** The lizardfolk makes one Bite attack and one Bone Pike attack.

**Bite.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 3 (1d6) Poison damage.

**Bone Pike.** m +4, reach 10 ft. *Hit:* 7 (1d10 + 2) Piercing damage.

**Poison Spit.** r +4, range 60 ft. *Hit:* 12 (3d6 + 2) Poison damage.


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