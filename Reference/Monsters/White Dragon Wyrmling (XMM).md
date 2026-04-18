---
type: pc
race: "Dragon (chromatic)"
class:
 - "White Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "White Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/xmm
---
###### White Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[White Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (chromatic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 5 | 10 | 11 |
| **Mod** | +2 | +0 | +2 | -3 | +0 | +0 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** cold

---

### Traits

**Ice Walk.** The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.


---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage plus 2 (1d4) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 12, each creature in a 15-foot Cone.  22 (5d8) Cold damage.  Half damage.


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