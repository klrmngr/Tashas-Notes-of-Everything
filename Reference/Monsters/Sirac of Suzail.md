---
type: pc
race: "Humanoid (human)"
class:
 - "Sirac of Suzail"
subClass:
 - "CR —"
cover: "Sirac of Suzail.png"
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
###### Sirac of Suzail
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Sirac of Suzail.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 11 | 12 | 13 | 16 |
| **Mod** | +2 | +3 | +0 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Orc
**Skills:** Athletics +4, Insight +3, Survival +3

---

### Traits

**Roleplaying Information.** An acolyte of Torm, Sirac grew up on the streets of Suzail, the capital of Cormyr. He came to Icewind Dale to become a knucklehead trout fisher but instead found religion. The misbegotten son of Artus Cimber, a renowned human adventurer, Sirac hasn't seen his father since he was a baby.
Ideal: "Without duty or loyalty, a man is nothing."
Bond: "Icewind Dale is where i belong for the rest of my life."
Flaw: "I am honest to a fault."


---

### Actions

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage. Sirac carries six darts.


---

### Reactions

**Parry.** Sirac adds 2 to his AC against on melee attack that would hit him. To do so, Sirac must see the attacker and be wielding a melee weapon.


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