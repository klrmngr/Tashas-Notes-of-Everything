---
type: pc
race: "Dragon (metallic)"
class:
 - "Bronze Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Bronze Dragon Wyrmling.png"
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
###### Bronze Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bronze Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (metallic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 12 | 11 | 15 |
| **Mod** | +3 | +0 | +2 | +1 | +0 | +2 |

**Speed:** 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Slashing damage.

**Lightning Breath (Recharge 5–6).** dex DC 12, each creature in a 40-foot-long, 5-foot-wide Line.  16 (3d10) Lightning damage.  Half damage.

**Repulsion Breath.** str DC 12, each creature in a 30-foot Cone.  The target is pushed up to 30 feet straight away from the dragon and has the Prone condition.


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