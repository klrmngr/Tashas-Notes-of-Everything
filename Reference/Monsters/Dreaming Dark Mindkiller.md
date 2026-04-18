---
type: pc
race: "Humanoid"
class:
 - "Dreaming Dark Mindkiller"
subClass:
 - "CR 11"
cover: "Dreaming Dark Mindkiller.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/11
  - source/efa
---
###### Dreaming Dark Mindkiller
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Dreaming Dark Mindkiller.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 180 (24d8 + 72) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 19 | 16 | 21 | 18 | 17 |
| **Mod** | +2 | +4 | +3 | +5 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 30 ft., passive Perception 18
**Languages:** Common, Quori; telepathy 120 ft.
**Saving Throws:** Dex +8, Int +9, Wis +8, Cha +7
**Skills:** Deception +7, Insight +8, Perception +8, Stealth +8
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The mindkiller makes two Nightmare Whisper attacks.

**Nightmare Whisper.** m,r +9, reach 5 ft. or range 30 ft. *Hit:* 27 (5d8 + 5) Psychic damage, and the target has the Frightened condition until the start of the mindkiller's next turn. If the target is already Frightened, it instead takes an extra 10 (3d6) Psychic damage.

**Primal Fear (1/Day).** wis DC 17, each creature in a 30-foot-radius Sphere centered on a point the mindkiller can see within 120 feet.  35 (10d6) Psychic damage, and the target has the Frightened condition until the start of the mindkiller's next turn. While Frightened in this way, the target can do only one of the following on each of its turns: move, take an action, or take a Bonus Action.  Half damage only.


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