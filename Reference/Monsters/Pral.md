---
type: pc
race: "Humanoid (human)"
class:
 - "Pral"
subClass:
 - "CR 1"
cover: "Pral.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/hotb
---
###### Pral
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Pral.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 14 | 14 | 11 | 14 |
| **Mod** | +2 | +3 | +2 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Saving Throws:** Dex +5
**Skills:** Athletics +4, Deception +4

---

### Actions

**Rapier.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage.

**Light Crossbow.** r +5, range 80/320 ft. *Hit:* 7 (1d8 + 3) Piercing damage.


---

### Reactions

**Parry.**  Pral is hit with a melee attack roll while holding a weapon.  Pral adds 2 to his AC against that attack, potentially causing the attack to miss.


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