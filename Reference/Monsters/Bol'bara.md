---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Bol'bara"
subClass:
 - "CR 3"
cover: "Bol'bara.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/egw
---
###### Bol'bara
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Bol'bara.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 (leather armor); 15 with mage armor |
> | :FasHeart: HP | 40 (9d6 + 9) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 10 | 13 | 14 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Goblin

---

### Traits

**Dark One's Blessing.** When Bol'bara reduces a hostile creature to 0 hit points, she gains 6 temporary hit points.

**Nimble Escape.** Bol'bara can take the Disengage or Hide action as a bonus action on each of her turns.


---

### Actions

**Multiattack.** Bol'bara makes two melee attacks.

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Eldritch Blast (Cantrip).** Ranged Spell Attack: +4 to hit, range 120 ft., one creature. *Hit:* 7 (1d10 + 2) force damage.


---

### Legendary Actions

### 

**Incorporeal Dash.** Bol'bara moves up to her speed. She can move through other creatures and objects as if they were 3. She takes 5 (1d10) force damage if she ends her turn inside an object.

**Zone of Calamity (Costs 2 Actions).** A 15-foot-radius sphere of magical confusion extends from a point Bol'bara can see within 60 feet of her and spreads around corners. Each creature that starts its turn in that area is treated as if targeted by the confusion spell (save DC 12). The sphere lasts as long as Bol'bara maintains concentration, up to 1 minute (as if concentrating on a spell).


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