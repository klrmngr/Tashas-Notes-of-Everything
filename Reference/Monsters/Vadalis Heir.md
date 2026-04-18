---
type: pc
race: "Humanoid (human)"
class:
 - "Vadalis Heir"
subClass:
 - "CR 4"
cover: "Vadalis Heir.png"
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
###### Vadalis Heir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Vadalis Heir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (human) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 15 | 10 | 17 | 13 |
| **Mod** | +1 | +3 | +2 | +0 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Sylvan
**Saving Throws:** Dex +5, Con +4, Wis +5
**Skills:** Animal Handling +7, Nature +4, Stealth +5

---

### Traits

**Pack Tactics.** The heir has Advantage on an attack roll against a creature if at least one of the heir's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The heir makes four attacks, using Scimitar or Lunar Wisp in any combination.

**Scimitar.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage plus 3 (1d6) Poison damage.

**Lunar Wisp.** r +5, range 60 ft. *Hit:* 9 (2d8) Radiant damage, and the target emits Dim Light in a 10-foot radius and can't benefit from the Invisible condition until the end of the heir's next turn.


---

### Bonus Actions

**Spur Beast.** The heir targets a Beast it can see within 30 feet. The target can take a Reaction to move up to half its Speed and make one melee attack.


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