---
type: pc
race: "Giant"
class:
 - "Crab Folk"
subClass:
 - "CR 3"
cover: "Crab Folk.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/3
  - source/mff
---
###### Crab Folk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Crab Folk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 7 | 9 | 9 |
| **Mod** | +4 | +0 | +3 | -2 | -1 | -1 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Common, Giant

---

### Traits

**Limited Amphibiousness.** The crab folk can breathe air and water, but it needs to be submerged once every 24 hours to avoid suffocating.


---

### Actions

**Multiattack.** The crab folk makes two claw attacks.

**Claw.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage and the target is grappled (escape DC 14). Until this grapple ends, the crab folk can automatically hit the target with its claw, and the crab folk can't make attacks with that claw against other targets. The crab folk has two claws, each of which can grapple only one target.


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