---
type: pc
race: "Humanoid (human)"
class:
 - "Amrik Vanthampur"
subClass:
 - "CR 3"
cover: "Amrik Vanthampur.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bgdia
---
###### Amrik Vanthampur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Amrik Vanthampur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (leather armor, charisma modifier) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 12 | 14 | 14 | 15 |
| **Mod** | +1 | +4 | +1 | +2 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Infernal
**Skills:** Acrobatics +6, Athletics +3, Deception +6, Insight +6

---

### Traits

**Suave Defense.** While Amrik is wearing light or no armor and wielding no shield, his AC includes his Charisma modifier.


---

### Actions

**Multiattack.** Amrik makes three dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.

**Smoke Bomb (1/Day).** Amrik hurls a smoke bomb up to 20 feet away. The bomb explodes on impact, creating a cloud of black smoke that fills a 10-foot-radius sphere. The area within the cloud is heavily obscured. A strong wind disperses the cloud, which otherwise remains until the end of Amrik's next turn.


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