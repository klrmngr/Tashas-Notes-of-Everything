---
type: pc
race: "Monstrosity"
class:
 - "Yakfolk Warrior"
subClass:
 - "CR 3"
cover: "Yakfolk Warrior.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/skt
---
###### Yakfolk Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Yakfolk Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (leather armor) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 15 | 14 | 15 | 14 |
| **Mod** | +4 | +0 | +2 | +2 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Yikaria
**Skills:** Deception +4, Survival +4

---

### Traits

**Possession (Recharges after a Short or Long Rest).** The yakfolk attempts to magically possess a humanoid or giant. The yakfolk must touch the target throughout a short rest, or the attempt fails. At the end of the rest, the target must succeed on a DC 12 Constitution saving throw or be possessed by the yakfolk, which disappears with everything it is carrying and wearing. Until the possession ends, the target is incapacitated, loses control of its body, and is unaware of its surroundings. The yakfolk now controls the body and can't be targeted by any attack, spell, or other effect, and it retains its alignment; its Intelligence, Wisdom, and Charisma scores; and its proficiencies. It otherwise uses the target's statistics, except the target's knowledge, class features, feats, and proficiencies.
The possession lasts until either the body drops to 0 hit points, the yakfolk ends the possession as an action, or the yakfolk is forced out of the body by an effect such as the dispel evil and good spell. When the possession ends, the yakfolk reappears in an unoccupied space within 5 feet of the body and is stunned until the end of its next turn. If the host body dies while it is possessed by the yakfolk, the yakfolk dies as well, and its body doesn't reappear.


---

### Actions

**Multiattack.** The yakfolk makes two attacks, either with its greatsword or its longbow.

**Greatsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 18 (4d6 + 4) slashing damage.

**Longbow.** Ranged Weapon Attack: +2 to hit, range 150/600 ft., one target. *Hit:* 9 (2d8) piercing damage.


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