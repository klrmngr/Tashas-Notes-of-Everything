---
type: pc
race: "Humanoid (human)"
class:
 - "Darathra Shendrel"
subClass:
 - "CR —"
cover: "Darathra Shendrel.png"
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
###### Darathra Shendrel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Darathra Shendrel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 14 (breastplate) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 11 | 11 | 15 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** History +2, Intimidation +4, Investigation +2, Perception +2, Persuasion +4

---

### Traits

**Brave.** Darathra has advantage on saving throws against being frightened

**Roleplaying Information.** As the Lord Protector of Triboar and a secret agent of the Harpers, Darathra has sworn an oath to defend the town. She takes her duty very seriously. In addition to her gear, Darathra has an unarmored warhorse named Buster.
Ideal: "Good people should be given every chance to prosper, free of tyranny."
Bond: "I'll lay down my life to protect Triboar and its citizens."
Flaw: "I refuse to back down. Push me, and I'll push back."


---

### Actions

**Multiattack.** Darathra makes two melee attacks.

**Greatsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage. Darathra carries twenty crossbow bolts.


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