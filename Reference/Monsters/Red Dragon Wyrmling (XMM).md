---
type: pc
race: "Dragon (chromatic)"
class:
 - "Red Dragon Wyrmling"
subClass:
 - "CR 4"
cover: "Red Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/4
  - source/xmm
---
###### Red Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Red Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Dragon (chromatic) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +0 | +3 | +1 | +0 | +2 |

**Speed:** 30 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** fire

---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +6, reach 5 ft. *Hit:* 9 (1d10 + 4) Slashing damage plus 3 (1d6) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 13, each creature in a 15-foot Cone.  24 (7d6) Fire damage.  Half damage.


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