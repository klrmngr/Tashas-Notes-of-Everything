---
type: pc
race: "Dragon (chromatic)"
class:
 - "Young Blue Dragon"
subClass:
 - "CR 9"
cover: "Young Blue Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/xmm
---
###### Young Blue Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Blue Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon (chromatic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 152 (16d10 + 64) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 19 | 14 | 13 | 17 |
| **Mod** | +5 | +0 | +4 | +2 | +1 | +3 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 19
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +5
**Skills:** Perception +9, Stealth +4
**Damage Immunities:** lightning

---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +9, reach 10 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 5 (1d10) Lightning damage.

**Lightning Breath (Recharge 5–6).** dex DC 16, each creature in a 60-foot-long, 5-foot-wide Line.  55 (10d10) Lightning damage.  Half damage.


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