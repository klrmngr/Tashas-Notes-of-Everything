---
type: pc
race: "Dragon (metallic)"
class:
 - "Young Brass Dragon"
subClass:
 - "CR 6"
cover: "Young Brass Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/6
  - source/xmm
---
###### Young Brass Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Brass Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Dragon (metallic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 110 (13d10 + 39) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +0 | +3 | +1 | +0 | +2 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Dex +3, Wis +3
**Skills:** Perception +6, Persuasion +5, Stealth +3
**Damage Immunities:** fire

---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace two attacks with a use of Sleep Breath.

**Rend.** m +7, reach 10 ft. *Hit:* 15 (2d10 + 4) Slashing damage.

**Fire Breath (Recharge 5–6).** dex DC 14, each creature in a 40-foot-long, 5-foot-wide Line.  38 (11d6) Fire damage.  Half damage.

**Sleep Breath.** con DC 14, each creature in a 30-foot Cone.  The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. 2 The target has the Unconscious condition for 1 minute. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.


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