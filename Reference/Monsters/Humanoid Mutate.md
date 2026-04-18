---
type: pc
race: "Aberration"
class:
 - "Humanoid Mutate"
subClass:
 - "CR 4"
cover: "Humanoid Mutate.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/4
  - source/pabtso
---
###### Humanoid Mutate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Humanoid Mutate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 14 | 11 | 13 | 15 |
| **Mod** | +1 | +4 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Common, telepathy 60 ft.
**Skills:** Perception +3, Stealth +6
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the mutate has disadvantage on attack rolls.


---

### Actions

**Multiattack.** The mutate makes two Unarmed Strike or Nightmare Blast attacks.

**Unarmed Strike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage plus 10 (3d6) psychic damage.

**Nightmare Blast.** Ranged Weapon Attack: +6 to hit, range 60 ft., one creature. *Hit:* 7 (2d6) psychic damage, and the target must succeed on a DC 12 Wisdom saving throw or have the frightened condition until the start of the mutate's next turn.


---

### Reactions

**Defensive Flight.** Immediately after taking damage, the mutate flies up to its speed. This movement doesn't provoke opportunity attacks.


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