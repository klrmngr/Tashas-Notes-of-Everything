---
type: pc
race: "Dragon (metallic)"
class:
 - "Silver Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Silver Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/xmm
---
###### Silver Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Silver Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (metallic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +0 | +3 | +1 | +0 | +2 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** cold

---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +6, reach 5 ft. *Hit:* 9 (1d10 + 4) Piercing damage.

**Cold Breath (Recharge 5–6).** con DC 13, each creature in a 15-foot Cone.  18 (4d8) Cold damage.  Half damage.

**Paralyzing Breath.** con DC 13, each creature in a 15-foot Cone. 1 The target has the Incapacitated condition until the end of its next turn, when it repeats the save. 2 The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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