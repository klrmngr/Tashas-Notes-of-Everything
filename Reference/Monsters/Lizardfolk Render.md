---
type: pc
race: "Humanoid (lizardfolk)"
class:
 - "Lizardfolk Render"
subClass:
 - "CR 3"
cover: "Lizardfolk Render.png"
campaign:
locations:
tags:
  - race/lizardfolk
  - affinity/hostile
  - type/humanoid
  - size/large
  - cr/3
  - source/gos
---
###### Lizardfolk Render
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Lizardfolk Render.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Humanoid (lizardfolk) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Humanoid (lizardfolk) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 7 | 12 | 7 |
| **Mod** | +3 | +0 | +2 | -2 | +1 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Draconic
**Skills:** Athletics +5, Perception +3, Survival +5

---

### Traits

**Blood Frenzy.** The render has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Hold Breath.** The render can hold its breath for 15 minutes.


---

### Actions

**Multiattack.** The render makes two attacks: one with its claws and one with its bite.

**Claws.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage.

**Rend the Field (Recharge 5–6).** The render makes a claw attack against each creature of its choice within 10 feet of it. A creature hit by this attack must succeed on a DC 13 Strength saving throw or be knocked prone.


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