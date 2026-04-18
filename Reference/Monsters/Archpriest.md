---
type: pc
race: "Humanoid (cleric)"
class:
 - "Archpriest"
subClass:
 - "CR 12"
cover: "Archpriest.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/12
  - source/xmm
---
###### Archpriest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Archpriest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 240 (32d8 + 96) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 14 | 21 | 14 |
| **Mod** | +3 | +1 | +3 | +2 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Common plus two other languages
**Saving Throws:** Str +7, Con +7, Int +6, Wis +9
**Skills:** Insight +9, Medicine +9, Perception +9, Religion +10

---

### Actions

**Multiattack.** The archpriest makes three Radiant Burst attacks.

**Radiant Burst.** m,r +9, reach 5 ft. or range 60 ft. *Hit:* 27 (4d10 + 5) Radiant damage.

**Holy Word (Recharge 4–6).** wis DC 17, each enemy in a 20-foot Emanation originating from the archpriest.  21 (6d6) Radiant damage, and the target has the Stunned condition until the end of the archpriest's next turn.  Half damage only.


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