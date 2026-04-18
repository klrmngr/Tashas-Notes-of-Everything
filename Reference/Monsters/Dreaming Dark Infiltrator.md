---
type: pc
race: "Humanoid"
class:
 - "Dreaming Dark Infiltrator"
subClass:
 - "CR 7"
cover: "Dreaming Dark Infiltrator.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/efa
---
###### Dreaming Dark Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Dreaming Dark Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 15 | 18 | 16 | 17 |
| **Mod** | +2 | +3 | +2 | +4 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 30 ft., passive Perception 13
**Languages:** Common, Quori; telepathy 120 ft.
**Saving Throws:** Int +7, Wis +6, Cha +6
**Skills:** Deception +6, Insight +6, Stealth +6
**Damage Resistances:** psychic

---

### Actions

**Multiattack.** The infiltrator makes three Mind Blade attacks.

**Mind Blade.** m,r +7, reach 5 ft. or range 30 ft. *Hit:* 14 (3d6 + 4) Psychic damage.


---

### Bonus Actions

**Mind Curse.** wis DC 15, one creature hit by the infiltrator's Mind Blade attack this turn.  The target takes 14 (4d6) Psychic damage and is cursed. While cursed in this way, it has Disadvantage on attack rolls against the infiltrator, and the infiltrator always knows its location while it and the infiltrator are on the same plane of existence. A cursed creature repeats the save whenever it finishes a Short or Long Rest, ending the effect on itself on a success.  Half damage only.


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