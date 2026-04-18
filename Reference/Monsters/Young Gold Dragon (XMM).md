---
type: pc
race: "Dragon (metallic)"
class:
 - "Young Gold Dragon"
subClass:
 - "CR 10"
cover: "Young Gold Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/10
  - source/xmm
---
###### Young Gold Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Gold Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Dragon (metallic) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 21 | 16 | 13 | 20 |
| **Mod** | +6 | +2 | +5 | +3 | +1 | +5 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 19
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +5
**Skills:** Insight +5, Perception +9, Persuasion +9, Stealth +6
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The dragon can breathe air and water.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Weakening Breath.

**Rend.** m +10, reach 10 ft. *Hit:* 17 (2d10 + 6) Slashing damage.

**Fire Breath (Recharge 5–6).** dex DC 17, each creature in a 30-foot Cone.  55 (10d10) Fire damage.  Half damage.

**Weakening Breath.** str DC 17, each creature that isn't currently affected by this breath in a 30-foot Cone.  The target has Disadvantage on Strength-based D20 Tests and subtracts 3 (1d6) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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