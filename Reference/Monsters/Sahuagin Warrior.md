---
type: pc
race: "Fiend"
class:
 - "Sahuagin Warrior"
subClass:
 - "CR 1/2"
cover: "Sahuagin Warrior.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Sahuagin Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sahuagin Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 12 | 12 | 13 | 9 |
| **Mod** | +1 | +0 | +1 | +1 | +1 | -1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** Sahuagin
**Skills:** Perception +5
**Damage Resistances:** acid; cold

---

### Traits

**Blood Frenzy.** The sahuagin has Advantage on attack rolls against any creature that doesn't have all its Hit Points.

**Limited Amphibiousness.** The sahuagin can breathe air and water, but it must be submerged at least once every 4 hours to avoid suffocating outside water.

**Shark Telepathy.** The sahuagin can magically control sharks within 120 feet of itself, using a special telepathy.


---

### Actions

**Multiattack.** The sahuagin makes two Claw attacks.

**Claw.** m +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Slashing damage.


---

### Bonus Actions

**Aquatic Charge.** The sahuagin swims up to its Swim Speed straight toward an enemy it can see.


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