---
type: pc
race: "Construct"
class:
 - "Steel Defender"
subClass:
 - "CR —"
cover: "Steel Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/tce
---
###### Steel Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Steel Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 2 + your Intelligence modifier + five times your artificer level (the defender has a number of Hit Dice [d8s] equal to your artificer level) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 4 | 10 | 6 |
| **Mod** | +2 | +1 | +2 | -3 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10 + (PB × 2)
**Languages:** understands the languages you speak
**Saving Throws:** Dex +1 plus PB, Con +2 plus PB
**Skills:** Athletics +2 plus PB, Perception +0 plus PB × 2
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Vigilant.** The defender can't be surprised.


---

### Actions

**Force-Empowered Rend.** Melee Weapon Attack:  to hit, reach 5 ft., one target you can see. *Hit:* 1d8 + PB force damage.

**Repair (3/Day).** The magical mechanisms inside the defender restore 2d8 + PB hit points to itself or to one construct or object within 5 feet of it.


---

### Reactions

**Deflect Attack.** The defender imposes disadvantage on the attack roll of one creature it can see that is within 5 feet of it, provided the attack roll is against a creature other than the defender.


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