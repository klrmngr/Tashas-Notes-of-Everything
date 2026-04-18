---
type: pc
race: "Beast"
class:
 - "Haungharassk"
subClass:
 - "CR 0"
cover: "Haungharassk.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/0
  - source/wdmm
---
###### Haungharassk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Haungharassk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 6 |
> | :FasHeart: HP | 52 (7d12 + 7) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 3 | 13 | 3 | 10 | 3 |
| **Mod** | +5 | -4 | +1 | -4 | +0 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Salt Sensitivity.** A pound of salt thrown onto the snail's skin deals 1d6 acid damage to the creature.

**Magical Properties.** A creature that uses an action to touch the living snail gains 6 temporary hit points that last for 24 hours. Any creature or object that touches the living snail also gains the benefit of a remove curse spell. The snail loses these magical properties if it dies.

**Spider Climb.** The snail can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


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