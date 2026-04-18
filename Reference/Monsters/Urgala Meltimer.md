---
type: pc
race: "Humanoid (human)"
class:
 - "Urgala Meltimer"
subClass:
 - "CR —"
cover: "Urgala Meltimer.png"
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
###### Urgala Meltimer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Urgala Meltimer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 (leather armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 12 | 14 | 13 |
| **Mod** | +3 | +1 | +2 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Giant
**Skills:** Athletics +5, Intimidation +3

---

### Traits

**Giant Slayer.** Any weapon attack that Urgala makes against a giant deals an extra 7 (2d6) damage on a hit.

**Roleplaying Information.** A retired adventurer, Urgala owns a respectable inn, the North shield House, and she doesn't want to see it or her neighbors' homes destroyed. She has no tolerance for monsters or bullies.
Ideal: "We live in a violent world, and sometimes violence is necessary for survival."
Bond: "My home is my life. Threaten it, and I'll hurt you."
Flaw: "I know how treacherous and greedy adventurers can be. I don't trust them—any of them."


---

### Actions

**Multiattack.** Urgala makes two attacks with her morningstar or her shortbow.

**Morningstar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Shortbow.** Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 1) piercing damage. Urgala carries a quiver of twenty arrows.


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