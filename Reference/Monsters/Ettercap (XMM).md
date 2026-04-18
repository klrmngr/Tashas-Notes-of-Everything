---
type: pc
race: "Monstrosity"
class:
 - "Ettercap"
subClass:
 - "CR 2"
cover: "Ettercap.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/xmm
---
###### Ettercap
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ettercap.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 13 | 7 | 12 | 8 |
| **Mod** | +2 | +2 | +1 | -2 | +1 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4, Survival +3

---

### Traits

**Spider Climb.** The ettercap can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The ettercap ignores movement restrictions caused by webs, and the ettercap knows the location of any other creature in contact with the same web.


---

### Actions

**Multiattack.** The ettercap makes one Bite attack and one Claw attack.

**Bite.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 2 (1d4) Poison damage, and the target has the Poisoned condition until the start of the ettercap's next turn.

**Claw.** m +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Slashing damage.

**Web Strand (Recharge 5–6).** dex DC 12, one Large or smaller creature the ettercap can see within 30 feet.  The target has the Restrained condition until the web is destroyed (AC 10; HP 5; Vulnerability to Fire damage; Immunity to Bludgeoning, Poison, and Psychic damage).


---

### Bonus Actions

**Reel.** The ettercap pulls one creature within 30 feet of itself that is Restrained by its Web Strand up to 25 feet straight toward itself.


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