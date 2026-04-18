---
type: pc
race: "Monstrosity"
class:
 - "Doppelganger"
subClass:
 - "CR 3"
cover: "Doppelganger.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/xmm
---
###### Doppelganger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Doppelganger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 11 | 12 | 14 |
| **Mod** | +0 | +4 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common plus three other languages
**Skills:** Deception +6, Insight +3
**Condition Immunities:** charmed

---

### Actions

**Multiattack.** The doppelganger makes two Slam attacks and uses Unsettling Visage if available.

**Slam.** m +6 (with Advantage during the first round of each combat), reach 5 ft. *Hit:* 11 (2d6 + 4) Bludgeoning damage.

**Unsettling Visage (Recharge 6).** wis DC 12, each creature in a 15-foot Emanation originating from the doppelganger that can see the doppelganger.  The target has the Frightened condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Bonus Actions

**Shape-Shift.** The doppelganger shape-shifts into a Medium or Small Humanoid, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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