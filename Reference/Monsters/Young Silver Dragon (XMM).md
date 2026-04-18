---
type: pc
race: "Dragon (metallic)"
class:
 - "Young Silver Dragon"
subClass:
 - "CR 9"
cover: "Young Silver Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/9
  - source/xmm
---
###### Young Silver Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Silver Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Dragon (metallic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 168 (16d10 + 80) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 14 | 11 | 19 |
| **Mod** | +6 | +0 | +5 | +2 | +0 | +4 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +4
**Skills:** History +6, Perception +8, Stealth +4
**Damage Immunities:** cold

---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Paralyzing Breath.

**Rend.** m +10, reach 10 ft. *Hit:* 15 (2d8 + 6) Slashing damage.

**Cold Breath (Recharge 5–6).** con DC 17, each creature in a 30-foot Cone.  49 (11d8) Cold damage.  Half damage.

**Paralyzing Breath.** con DC 17, each creature in a 30-foot Cone. 1 The target has the Incapacitated condition until the end of its next turn, when it repeats the save. 2 The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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