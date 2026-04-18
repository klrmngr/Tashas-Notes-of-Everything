---
type: pc
race: "Construct"
class:
 - "Rusted Behemoth"
subClass:
 - "CR 9"
cover: "Rusted Behemoth.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/9
  - source/fraif
---
###### Rusted Behemoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Rusted Behemoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 157 (15d12 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 19 | 6 | 12 | 6 |
| **Mod** | +6 | +0 | +4 | -2 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Common, Giant
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Actions

**Multiattack.** The Rusted makes three attacks, using Slam or Rusted Shot Put in any combination.

**Slam.** m +10, reach 10 ft. *Hit:* 20 (4d6 + 6) Bludgeoning damage.

**Rusted Shot Put.** r +10, range 60/240 ft. *Hit:* 15 (2d8 + 6) Bludgeoning damage, and the target has the Poisoned condition until the end of its next turn.


---

### Reactions

**Rust-Riddled Hide.**  The Rusted is hit by an attack roll that deals Bludgeoning, Piercing, or Slashing damage. dcon DC 16, each creature of the Rusted's choice in a 5-foot Emanation originating from the Rusted.  the target has the Poisoned condition until the end of the target's next turn.


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