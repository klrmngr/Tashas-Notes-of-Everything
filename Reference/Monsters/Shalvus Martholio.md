---
type: pc
race: "Humanoid (human)"
class:
 - "Shalvus Martholio"
subClass:
 - "CR —"
cover: "Shalvus Martholio.png"
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
###### Shalvus Martholio
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Shalvus Martholio.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 12 | 14 | 14 |
| **Mod** | +0 | +2 | +0 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Elvish
**Skills:** Deception +4, Insight +4, Investigation +3, Perception +4, Sleight Of Hand +4, Stealth +4

---

### Traits

**Sneak Attack (1/Turn).** Shalvus deals an extra 7 (2d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Shalvus that isn't incapacitated and Shalvus doesn't have disadvantage on the attack roll.

**Roleplaying Information.** Nalaskur Thaelond of Bargewright Inn has entrusted the shepherd Shalvus with an important assignment: to figure out the best way by which Goldenfields can be brought under the Black Network's control. Shalvus believes that success will ensure his swift rise through the Zhentarim ranks.
Ideal: "I'll do what it takes to prove myself to the Zhentarim."
Bond: "I love animals, and I'm very protective of them."
Flaw: "I can't resist taking risks to feed my ambitions."


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if used with both hands.

**Hand Crossbow.** Ranged Weapon Attack: +2 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage. Shalvus carries ten crossbow bolts.


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