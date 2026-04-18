---
type: pc
race: "Fey"
class:
 - "Green Hag"
subClass:
 - "CR 3"
cover: "Green Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/xmm
---
###### Green Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Green Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 13 | 14 | 14 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common, Elvish, Sylvan
**Skills:** Arcana +5, Deception +4, Perception +4, Stealth +3

---

### Traits

**Amphibious.** The hag can breathe air and water.

**Mimicry.** The hag can mimic animal sounds and humanoid voices. A creature that hears the sounds can tell they are imitations only with a successful DC 14 Wisdom (Insight) check.


---

### Actions

**Multiattack.** The hag makes two Claw attacks.

**Claw.** m +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing damage plus 3 (1d6) Poison damage.


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