---
type: pc
race: "Humanoid (human)"
class:
 - "Duvessa Shane"
subClass:
 - "CR —"
cover: "Duvessa Shane.png"
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
###### Duvessa Shane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Duvessa Shane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 10 | 16 | 14 | 16 |
| **Mod** | +0 | +0 | +0 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish, Giant, Orc
**Skills:** Deception +5, Insight +4, Persuasion +5

---

### Traits

**Roleplaying Information.** The daughter of a Waterdhavian trader and a tavern server, Duvessa has her mother's talent for negotiation and her father's charm. As the first woman to serve as Town Speaker of Bryn Shander, and a young one at that, she has much to prove.
Ideal: "The people of Icewind Dale are survivors. They can weather any storm."
Bond: "My mother taught me what it means to be a good leader. I won't disappoint her."
Flaw: "I don't give an inch in any argument of conflict."


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage. Duvessa carries only one dagger.


---

### Reactions

**Parry.** Duvessa adds 2 to her AC against one melee attack that would hit her. To do so, Duvessa must see the attacker and be wielding a melee weapon.


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