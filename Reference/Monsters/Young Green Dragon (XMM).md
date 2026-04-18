---
type: pc
race: "Dragon (chromatic)"
class:
 - "Young Green Dragon"
subClass:
 - "CR 8"
cover: "Young Green Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/8
  - source/xmm
---
###### Young Green Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Green Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Dragon (chromatic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 17 | 16 | 13 | 15 |
| **Mod** | +4 | +1 | +3 | +3 | +1 | +2 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +4
**Skills:** Deception +5, Perception +7, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Slashing damage plus 7 (2d6) Poison damage.

**Poison Breath (Recharge 5–6).** con DC 14, each creature in a 30-foot Cone.  42 (12d6) Poison damage.  Half damage.


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