---
type: pc
race: "Humanoid"
class:
 - "Death Cultist"
subClass:
 - "CR 8"
cover: "Death Cultist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Death Cultist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Cultist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 18 | 12 | 16 | 14 |
| **Mod** | +4 | +1 | +4 | +1 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Saving Throws:** Con +7, Wis +6
**Skills:** Insight +6, Perception +6, Religion +4

---

### Actions

**Multiattack.** The cultist makes three attacks, using Dread Scythe or Deathly Ray in any combination.

**Dread Scythe.** m +7, reach 10 ft. *Hit:* 9 (1d10 + 4) Slashing damage plus 11 (2d10) Necrotic damage, and the target can't regain Hit Points until the end of its next turn.

**Deathly Ray.** r +6, range 120 ft. *Hit:* 22 (4d10) Necrotic damage.


---

### Bonus Actions

**Spirit Wail (Recharge 5–6).** wis DC 14, each creature in a 20-foot Emanation originating from the cultist.  14 (4d6) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.


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