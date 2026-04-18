---
type: pc
race: "Monstrosity"
class:
 - "Sea Spawn"
subClass:
 - "CR 1"
cover: "Sea Spawn.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/mpmm
---
###### Sea Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Sea Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 8 | 15 | 6 | 10 | 8 |
| **Mod** | +2 | -1 | +2 | -2 | +0 | -1 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Aquan and Common but can't speak

---

### Traits

**Limited Amphibiousness.** The sea spawn can breathe air and water, but it needs to be submerged in the sea at least once a day for 1 minute to avoid suffocating.


---

### Actions

**Multiattack.** The sea spawn makes two Unarmed Strike attacks and one Piscine Anatomy attack.

**Unarmed Strike.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Piscine Anatomy.** The sea spawn uses one of the following options (choose one or roll a d6):
- **1–2: Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.
- **3–4: Poison Quills.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 3 (1d6) poison damage, and the target must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- **5–6: Tentacle.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, and the target is grappled (escape DC 12) if it is a Medium or smaller creature. Until this grapple ends, the sea spawn can't use this tentacle on another target.


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