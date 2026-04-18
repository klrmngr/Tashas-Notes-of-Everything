---
type: pc
race: "Dragon (metallic)"
class:
 - "Copper Dragon Wyrmling"
subClass:
 - "CR 1"
cover: "Copper Dragon Wyrmling.png"
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
###### Copper Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Copper Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Dragon (metallic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 13 | 14 | 11 | 13 |
| **Mod** | +2 | +1 | +1 | +2 | +0 | +1 |

**Speed:** 30 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +3, Wis +2
**Skills:** Perception +4, Stealth +3
**Damage Immunities:** acid

---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 7 (1d10 + 2) Slashing damage.

**Acid Breath (Recharge 5–6).** dex DC 11, each creature in a 20-foot-long, 5-foot-wide Line.  18 (4d8) Acid damage.  Half damage.

**Slowing Breath.** con DC 11, each creature in a 15-foot Cone.  The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.


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