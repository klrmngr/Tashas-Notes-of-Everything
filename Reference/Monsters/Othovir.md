---
type: pc
race: "Humanoid (human)"
class:
 - "Othovir"
subClass:
 - "CR —"
cover: "Othovir.png"
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
###### Othovir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Othovir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 10 | 13 | 12 | 14 | 16 |
| **Mod** | +0 | +0 | +1 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Elvish
**Skills:** Deception +5, Insight +4, Persuasion +5

---

### Traits

**Roleplaying Information.** Othovir is a gifted harness-maker who doesn't talk about his family or where he came from. He cares about his business, his clients, and his good name.
Ideal: "Find what you do well, and do it to the best of your ability."
Bond: "I won't allow my name to be tarnished."
Flaw: "I get angry when others pry into my private life."


---

### Actions

**Rapier.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) piercing damage.


---

### Reactions

**Parry.** Othovir adds 2 to its AC against one melee attack that would hit him. To do so, Othovir must see the attacker and be wielding a melee weapon.


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