---
type: pc
race: "Humanoid (human)"
class:
 - "Death's Head of Bhaal"
subClass:
 - "CR 5"
cover: "Death's Head of Bhaal.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bgdia
---
###### Death's Head of Bhaal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Death's Head of Bhaal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 76 (8d8 + 40) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 20 | 20 | 14 | 13 | 16 |
| **Mod** | +5 | +5 | +5 | +2 | +1 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Intimidation +6, Perception +4, Persuasion +6, Stealth +11

---

### Traits

**Aura of Murder.** As long as the death's head is not incapacitated, hostile creatures within 5 feet of it gain vulnerability to piercing damage unless they have resistance or immunity to such damage.

**Magic Resistance.** The death's head has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The death's head uses Stunning Gaze and makes two dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.

**Stunning Gaze.** The death's head targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom saving throw or be stunned until the end of its next turn.


---

### Reactions

**Unstoppable (3/Day).** The death's head reduces the damage it takes from an attack to 0.


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