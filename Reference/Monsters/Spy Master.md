---
type: pc
race: "Humanoid"
class:
 - "Spy Master"
subClass:
 - "CR 10"
cover: "Spy Master.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/xmm
---
###### Spy Master
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spy Master.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 20 | 12 | 18 | 16 | 16 |
| **Mod** | +0 | +5 | +1 | +4 | +3 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 21
**Languages:** Common plus two other languages
**Saving Throws:** Dex +9, Con +5, Int +8, Wis +7
**Skills:** Deception +7, Insight +7, Investigation +8, Perception +11, Sleight Of Hand +9, Stealth +13

---

### Actions

**Multiattack.** The spy makes three attacks, using Rapier or Hand Crossbow in any combination.

**Rapier.** m +9, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing damage plus 7 (2d6) Poison damage.

**Hand Crossbow.** r +9, range 30/120 ft. *Hit:* 12 (2d6 + 5) Piercing damage plus 9 (2d8) Poison damage.

**Smoke Bomb (1/Day).** The spy throws a bomb to a point it can see within 30 feet of itself. con DC 16, each creature in a 20-foot-radius Sphere centered on that point.  28 (8d6) Poison damage, and the target has the Blinded condition until the end of the spy's next turn.  Half damage only.


---

### Bonus Actions

**Cunning Action.** The spy takes the Dash, Disengage, or Hide action.


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