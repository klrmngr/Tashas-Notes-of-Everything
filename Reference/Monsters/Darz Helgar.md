---
type: pc
race: "Humanoid (human)"
class:
 - "Darz Helgar"
subClass:
 - "CR —"
cover: "Darz Helgar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Darz Helgar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Darz Helgar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 12 | 10 | 11 | 11 |
| **Mod** | +2 | +2 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Skills:** Intimidation +2, Sleight Of Hand +4, Stealth +4

---

### Traits

**Sneak Attack (1/Turn).** Darz deals an extra 7 (2d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Darz that isn't incapacitated and Darz doesn't have disadvantage on the attack roll.

**Roleplaying Information.** In his youth, Darz was a member of the Xanathar Thieves' Guild in Waterdeep. After serving ten years in prison for his crimes, he cut all ties to the city and moved north to be a campground caretaker.
Ideal: "You can run from your past, but you can't hide from it."
Bond: "I've made a new life in Triboar. I'm not gonna run away this time. "
Flaw: "I have no regrets. I do whatever it takes to survive."


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Darz carries twenty sling stones.


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