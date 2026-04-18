---
type: pc
race: "Humanoid (human)"
class:
 - "Nine-Fingers Keene"
subClass:
 - "CR 5"
cover: "Nine-Fingers Keene.png"
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
###### Nine-Fingers Keene
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Nine-Fingers Keene.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (leather armor) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 14 | 13 | 17 | 14 |
| **Mod** | +1 | +4 | +2 | +1 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +7, Int +4
**Skills:** Acrobatics +10, Deception +5, Insight +6, Intimidation +5, Perception +6, Sleight Of Hand +10, Stealth +10

---

### Traits

**Cunning Action.** On each of her turns in combat, Nine-Fingers can use a bonus action to take the Dash, Disengage, or Hide action.

**Dagger Thrower.** Nine-Fingers adds double her proficiency bonus to the damage she deals on ranged attacks made with daggers (already factored into her attacks).


---

### Actions

**Multiattack.** Nine-Fingers attacks three times with her daggers.

**Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage, plus 6 piercing damage if it's a ranged attack.


---

### Reactions

**Uncanny Dodge.** Nine-Fingers halves the damage that she takes from an attack that hits her. She must be able to see the attacker.


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