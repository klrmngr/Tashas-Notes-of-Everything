---
type: pc
race: "Humanoid (human)"
class:
 - "Orien Enforcer"
subClass:
 - "CR 4"
cover: "Orien Enforcer.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/efa
---
###### Orien Enforcer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Orien Enforcer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (human) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 13 | 16 | 14 | 11 |
| **Mod** | +1 | +4 | +1 | +3 | +2 | +0 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus two other languages
**Saving Throws:** Dex +6, Wis +4
**Skills:** Acrobatics +6, Perception +4

---

### Actions

**Multiattack.** The enforcer makes three Dagger attacks. It can replace one attack with a use of Lightning Cage if available.

**Dagger.** m,r +6, reach 5 ft. or range 20/60 ft. *Hit:* 9 (2d4 + 4) Piercing damage plus 7 (2d6) Poison damage.

**Lightning Cage (Recharge 5–6).** con DC 13, each creature in a 20-foot-radius Sphere centered on a point the enforcer can see within 60 feet.  13 (3d8) Lightning damage, and the creature can't take Reactions until the end of the enforcer's next turn.  Half damage only.


---

### Reactions

**Temporal Disruption (1/Day).**  The enforcer takes damage from a melee attack.  The enforcer teleports up to 30 feet to an unoccupied space it can see. Each creature within 10 feet of the space the enforcer left must succeed on a DC 13 Constitution saving throw, or its Speed is halved until the start of the enforcer's next turn.


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