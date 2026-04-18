---
type: pc
race: "Humanoid"
class:
 - "Performer Maestro"
subClass:
 - "CR 6"
cover: "Performer Maestro.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/xmm
---
###### Performer Maestro
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Performer Maestro.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 14 | 13 | 14 | 19 |
| **Mod** | +1 | +4 | +2 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus one other language
**Saving Throws:** Dex +7, Cha +7
**Skills:** Acrobatics +10, Athletics +4, Perception +5, Performance +10, Stealth +7

---

### Actions

**Multiattack.** The performer makes three Rapier attacks.

**Rapier.** m +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 7 (2d6) Psychic damage.

**Beguiling Song.** wis DC 15, each creature in a 20-foot-radius Sphere centered on a point within 120 feet.  20 (3d10 + 4) Psychic damage, and the target has the Charmed condition until the end of the performer's next turn.  Half damage only.


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