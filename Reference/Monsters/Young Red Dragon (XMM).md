---
type: pc
race: "Dragon (chromatic)"
class:
 - "Young Red Dragon"
subClass:
 - "CR 10"
cover: "Young Red Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/10
  - source/xmm
---
###### Young Red Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Red Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Dragon (chromatic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 11 | 19 |
| **Mod** | +6 | +0 | +5 | +2 | +0 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +4
**Skills:** Perception +8, Stealth +4
**Damage Immunities:** fire

---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +10, reach 10 ft. *Hit:* 13 (2d6 + 6) Slashing damage plus 3 (1d6) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 17, each creature in a 30-foot Cone.  56 (16d6) Fire damage.  Half damage.


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