---
type: pc
race: "Aberration"
class:
 - "Roper"
subClass:
 - "CR 5"
cover: "Roper.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/xmm
---
###### Roper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Roper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 17 | 7 | 16 | 6 |
| **Mod** | +4 | -1 | +3 | -2 | +3 | -2 |

**Speed:** 10 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 16
**Languages:** —
**Skills:** Perception +6, Stealth +5

---

### Traits

**Spider Climb.** The roper can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The roper makes two Tentacle attacks, uses Reel, and makes two Bite attacks.

**Bite.** m +7, reach 5 ft. *Hit:* 17 (3d8 + 4) Piercing damage.

**Tentacle.** m +7, reach 60 ft. *Hit:* The target has the Grappled condition (escape DC 14) from one of six tentacles, and the target has the Poisoned condition until the grapple ends.
The tentacle can be damaged, freeing a creature it has Grappled when destroyed (AC 20, HP 10, Immunity to Poison and Psychic damage). Damaging the tentacle deals no damage to the roper, and a destroyed tentacle regrows at the start of the roper's next turn.

**Reel.** The roper pulls each creature Grappled by it up to 30 feet straight toward it.


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