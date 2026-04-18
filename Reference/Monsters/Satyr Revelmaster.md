---
type: pc
race: "Fey"
class:
 - "Satyr Revelmaster"
subClass:
 - "CR 6"
cover: "Satyr Revelmaster.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/6
  - source/xmm
---
###### Satyr Revelmaster
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Satyr Revelmaster.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 12 | 12 | 14 | 17 |
| **Mod** | +1 | +4 | +1 | +1 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Dex +7, Wis +5
**Skills:** Acrobatics +7, Perception +5, Performance +9

---

### Traits

**Magic Resistance.** The satyr has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The satyr makes three Prance attacks.

**Prance.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Bludgeoning damage, and the target has the Charmed condition until the start of the satyr's next turn.

**Fey Melody (Recharge 4–6).** The satyr conjures a charming or frightening song. wis DC 14, each enemy in a 60-foot Emanation originating from the satyr.  The target is subjected to the song's effect:
- **Charming.** The target has the Charmed condition for 1 minute. While Charmed, the target has the Incapacitated condition and uses all its movement to dance in place. The effect ends on the target if it takes any damage.
- **Frightening.** 10 (2d6 + 3) Psychic damage, and the target has the Frightened condition for 1 minute. If the target ends its turn out of line of sight from the satyr, the condition ends on it.


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