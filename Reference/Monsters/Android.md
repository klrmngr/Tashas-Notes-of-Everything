---
type: pc
race: "Construct"
class:
 - "Android"
subClass:
 - "CR 5"
cover: "Android.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/5
  - source/qftis
---
###### Android
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Android.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 15 | 12 | 13 | 10 |
| **Mod** | +4 | +4 | +2 | +1 | +1 | +0 |

**Speed:** 30 ft., fly 30 ft. ((hover; aerialist only)) (hover), swim 30 ft. ((diver only)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (sentry only), darkvision 60 ft., passive Perception 17
**Languages:** Common plus the languages spoken by its creator
**Saving Throws:** Con +5, Wis +4
**Skills:** History +4, Perception +7
**Damage Resistances:** acid; fire
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Design Specialization.** When the android is created, it gains one of six possible designs suited for its role (choose or roll a d6): 1, aerialist; 2, diplomat; 3, diver; 4, duelist; 5, medic; 6, sentry. This design determines certain traits in this stat block.

**Lightning Overload.** When the android takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the stunned condition until the start of its next turn.


---

### Actions

**Multiattack.** The android makes two Force Strike attacks.

**Force Strike.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 40/120 ft., one target. *Hit:* 15 (2d10 + 4) force damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or have the prone condition.


---

### Reactions

**Parry (Duelist Only).** The android adds 3 to its AC against one melee attack roll that would hit it. To do so, the android must see the attacker.


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