---
type: pc
race: "Humanoid (khoravar)"
class:
 - "Lyrandar Scion"
subClass:
 - "CR 4"
cover: "Lyrandar Scion.png"
campaign:
locations:
tags:
  - race/khoravar
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/efa
---
###### Lyrandar Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Lyrandar Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (khoravar) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Humanoid (khoravar) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 13 | 12 | 15 | 18 |
| **Mod** | +1 | +3 | +1 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common, Elvish
**Saving Throws:** Str +3, Dex +5
**Skills:** Acrobatics +5, Perception +4
**Damage Resistances:** lightning; thunder

---

### Actions

**Multiattack.** The scion makes two Thunderbolt attacks and uses Spellcasting.

**Thunderbolt.** m,r +6, reach 5 ft. or range 30 ft. *Hit:* 11 (2d6 + 4) Lightning damage plus 9 (2d8) Thunder damage. Critical *Hit:* The creature also has the Deafened condition for 1 minute.


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