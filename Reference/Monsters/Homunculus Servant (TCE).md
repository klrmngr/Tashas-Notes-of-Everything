---
type: pc
race: "Construct"
class:
 - "Homunculus Servant"
subClass:
 - "CR —"
cover: "Homunculus Servant.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/—
  - source/tce
---
###### Homunculus Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Homunculus Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 1 + your Intelligence modifier + your artificer level (the homunculus has a number of Hit Dice [d4s] equal to your artificer level) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 12 | 10 | 10 | 7 |
| **Mod** | -3 | +2 | +1 | +0 | +0 | -2 |

**Speed:** 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10 + (PB × 2)
**Languages:** understands the languages you speak
**Saving Throws:** Dex +2 plus PB
**Skills:** Perception +0 plus PB × 2, Stealth +2 plus PB
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Evasion.** If the homunculus is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. It can't use this trait if it's incapacitated.


---

### Actions

**Force Strike.** Ranged Weapon Attack:  to hit, range 30 ft., one target you can see. *Hit:* 1d4 + PB force damage.


---

### Reactions

**Channel Magic.** The homunculus delivers a spell you cast that has a range of touch. The homunculus must be within 120 feet of you.


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