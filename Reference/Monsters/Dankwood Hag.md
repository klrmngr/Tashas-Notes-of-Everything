---
type: pc
race: "Fey"
class:
 - "Dankwood Hag"
subClass:
 - "CR 3"
cover: "Dankwood Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/awm
---
###### Dankwood Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Dankwood Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 82 |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 13 | 14 | 14 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Amphibious.** The hag can breathe air and water.

**Mimicry (Green Hag).** The hag can mimic animal sounds and humanoid voices. A creature that hears the sounds can tell they are imitations with a successful DC 14 Wisdom (Insight) check.


---

### Actions

**Illusory Appearance.** The hag covers herself with a magical illusion that allows her to look like another creature of her general size and shape. The illusion ends when the hag chooses, or if she dies. A DC 20 Intelligence (Investigation) check will expose the hag's disguise.

**Invisible Passage.** The hag magically turns invisible until she attacks or casts a spell, or until her concentration ends. While invisible, she leaves no physical evidence of her passage, and can only be tracked by magic.

**Claws.** Melee Weapon Attack: +6 to hit, one target. *Hit:* 17 (2d8 + 4) slashing damage.


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