---
type: pc
race: "Elemental"
class:
 - "Invisible Stalker"
subClass:
 - "CR 6"
cover: "Invisible Stalker.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/6
  - source/xmm
---
###### Invisible Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Invisible Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 97 (13d10 + 26) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 14 | 10 | 15 | 11 |
| **Mod** | +3 | +4 | +2 | +0 | +2 | +0 |

**Speed:** 50 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 18
**Languages:** Common, Primordial (Auran)
**Skills:** Perception +8, Stealth +10
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Air Form.** The stalker can enter an enemy's space and stop there. It can move through a space as narrow as 1 inch without expending extra movement to do so.

**Invisibility.** The stalker has the Invisible condition.


---

### Actions

**Multiattack.** The stalker makes three Wind Swipe attacks. It can replace one attack with a use of Vortex.

**Wind Swipe.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Force damage.

**Vortex.** con DC 14, one Large or smaller creature in the stalker's space.  7 (1d8 + 3) Thunder damage, and the target has the Grappled condition (escape DC 13). Until the grapple ends, the target can't cast spells with a Verbal component and takes 7 (2d6) Thunder damage at the start of each of the stalker's turns.


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