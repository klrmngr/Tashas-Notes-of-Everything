---
type: pc
race: "Dragon (metallic)"
class:
 - "Brass Dragon Wyrmling"
subClass:
 - "CR 1"
cover: "Brass Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/1
  - source/xmm
---
###### Brass Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Brass Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Dragon (metallic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 13 | 10 | 11 | 13 |
| **Mod** | +2 | +0 | +1 | +0 | +0 | +1 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** fire

---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 7 (1d10 + 2) Slashing damage.

**Fire Breath (Recharge 5–6).** dex DC 11, each creature in a 20-foot-long, 5-foot-wide Line.  14 (4d6) Fire damage.  Half damage.

**Sleep Breath.** con DC 11, each creature in a 15-foot Cone.  The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. 2 The target has the Unconscious condition for 1 minute. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.


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