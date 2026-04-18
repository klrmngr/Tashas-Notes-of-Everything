---
type: pc
race: "Aberration (gith)"
class:
 - "Githyanki Dracomancer"
subClass:
 - "CR 16"
cover: "Githyanki Dracomancer.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/16
  - source/xmm
---
###### Githyanki Dracomancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Githyanki Dracomancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 255 (30d8 + 120) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 18 | 20 | 16 | 18 |
| **Mod** | +0 | +3 | +4 | +5 | +3 | +4 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 18
**Languages:** Common, Draconic, Gith
**Saving Throws:** Dex +8, Con +9, Int +10, Wis +8
**Skills:** Arcana +10, Perception +8

---

### Actions

**Multiattack.** The githyanki makes three Draconic Strike attacks.

**Draconic Strike.** m,r +10, reach 10 ft. or range 120 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 17 (5d6) Fire damage, and the target has the Frightened condition until the start of the githyanki's next turn.

**Conjured Dragon's Breath (Recharge 5–6).** dex DC 18, each creature in a 90-foot Cone.  27 (6d8) Fire damage plus 27 (6d8) Force damage.  Half damage.


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