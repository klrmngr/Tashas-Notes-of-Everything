---
type: pc
race: "Dragon (chromatic)"
class:
 - "Young Black Dragon"
subClass:
 - "CR 7"
cover: "Young Black Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/xmm
---
###### Young Black Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Black Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon (chromatic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +2 | +3 | +1 | +0 | +2 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +3
**Skills:** Perception +6, Stealth +5
**Damage Immunities:** acid

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +7, reach 10 ft. *Hit:* 9 (2d4 + 4) Slashing damage plus 3 (1d6) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 14, each creature in a 30-foot-long, 5-foot-wide Line.  49 (14d6) Acid damage.  Half damage.


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