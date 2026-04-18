---
type: pc
race: "Dragon (metallic)"
class:
 - "Young Copper Dragon"
subClass:
 - "CR 7"
cover: "Young Copper Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/xmm
---
###### Young Copper Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Copper Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon (metallic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 17 | 16 | 13 | 15 |
| **Mod** | +4 | +1 | +3 | +3 | +1 | +2 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +4
**Skills:** Deception +5, Perception +7, Stealth +4
**Damage Immunities:** acid

---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Slowing Breath.

**Rend.** m +7, reach 10 ft. *Hit:* 15 (2d10 + 4) Slashing damage.

**Acid Breath (Recharge 5–6).** dex DC 14, each creature in a 40-foot-long, 5-foot-wide Line.  40 (9d8) Acid damage.  Half damage.

**Slowing Breath.** con DC 14, each creature in a 30-foot Cone.  The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.


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