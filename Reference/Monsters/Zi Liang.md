---
type: pc
race: "Humanoid (human)"
class:
 - "Zi Liang"
subClass:
 - "CR —"
cover: "Zi Liang.png"
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
###### Zi Liang
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Zi Liang.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 11 | 14 | 16 | 11 |
| **Mod** | +1 | +2 | +0 | +2 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Elvish, Goblin
**Skills:** Acrobatics +4, Athletics +3, Perception +5, Stealth +4

---

### Traits

**Unarmored Defense.** While Zi is wearing no armor and wielding no shield, her AC includes her Wisdom modifier.

**Roleplaying Information.** Zi Liang is a devout worshiper of Chauntea, the Earth Mother. She has considerably less faith in Goldenfields' defenders, so she patrols the temple-farm during her off-duty hours.
Ideal: "If we faithfully tend to our gardens and our fields, Chauntea will smile upon us."
Bond: "Goldenfields is the breadbasket of the North. People depend on its safety and prosperity, and I'll do what must be done to protect it."
Flaw: "I don't trust authority. I do what my heart says is right."


---

### Actions

**Multiattack.** Zi makes two melee attacks.

**Quarterstaff.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with both hands.

**Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage. Zi carries twenty sling stones.


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