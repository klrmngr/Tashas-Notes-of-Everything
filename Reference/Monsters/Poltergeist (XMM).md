---
type: pc
race: "Undead"
class:
 - "Poltergeist"
subClass:
 - "CR 2"
cover: "Poltergeist.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/2
  - source/xmm
---
###### Poltergeist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Poltergeist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 14 | 11 | 10 | 10 | 14 |
| **Mod** | -5 | +2 | +0 | +0 | +0 | +2 |

**Speed:** 5 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common plus one other language
**Damage Resistances:** acid; bludgeoning; cold; fire; lightning; piercing; slashing; thunder
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Incorporeal Movement.** The poltergeist can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The poltergeist makes one Object Slam attack and uses Telekinetic Thrust.

**Object Slam.** m,r +4, reach 5 ft. or range 30 ft. *Hit:* 7 (2d4 + 2) Bludgeoning damage.

**Telekinetic Thrust.** str DC 12, one creature the poltergeist can see within 30 feet.  9 (2d6 + 2) Force damage, and the target is pushed up to 30 feet straight away from the poltergeist.


---

### Bonus Actions

**Vanish.** The poltergeist gives itself the Invisible condition or ends that condition on itself.


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