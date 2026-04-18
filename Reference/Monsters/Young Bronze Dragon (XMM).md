---
type: pc
race: "Dragon (metallic)"
class:
 - "Young Bronze Dragon"
subClass:
 - "CR 8"
cover: "Young Bronze Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/8
  - source/xmm
---
###### Young Bronze Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Bronze Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Dragon (metallic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 19 | 14 | 13 | 17 |
| **Mod** | +5 | +0 | +4 | +2 | +1 | +3 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 17
**Languages:** Common, Draconic
**Saving Throws:** Dex +3, Wis +4
**Skills:** Insight +4, Perception +7, Stealth +3
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Repulsion Breath.

**Rend.** m +8, reach 10 ft. *Hit:* 16 (2d10 + 5) Slashing damage.

**Lightning Breath (Recharge 5–6).** dex DC 15, each creature in a 60-foot-long, 5-foot-wide Line.  49 (9d10) Lightning damage.  Half damage.

**Repulsion Breath.** str DC 15, each creature in a 30-foot Cone.  The target is pushed up to 40 feet straight away from the dragon and has the Prone condition.


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