---
type: pc
race: "Dragon (metallic)"
class:
 - "Gold Dragon Wyrmling"
subClass:
 - "CR 3"
cover: "Gold Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/3
  - source/xmm
---
###### Gold Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gold Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Dragon (metallic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 17 | 14 | 11 | 16 |
| **Mod** | +4 | +2 | +3 | +2 | +0 | +3 |

**Speed:** 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +4, Wis +2
**Skills:** Perception +4, Stealth +4
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +6, reach 5 ft. *Hit:* 9 (1d10 + 4) Slashing damage.

**Fire Breath (Recharge 5–6).** dex DC 13, each creature in a 15-foot Cone.  22 (4d10) Fire damage.  Half damage.

**Weakening Breath.** str DC 13, each creature that isn't currently affected by this breath in a 15-foot Cone.  The target has Disadvantage on Strength-based D20 Tests and subtracts 2 (1d4) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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