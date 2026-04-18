---
type: pc
race: "Plant"
class:
 - "Needle Lord"
subClass:
 - "CR 3"
cover: "Needle Lord.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/3
  - source/mff
---
###### Needle Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Needle Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 14 | 11 | 15 | 12 |
| **Mod** | +4 | +0 | +2 | +0 | +2 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 14
**Languages:** Sylvan
**Skills:** Athletics +6, Perception +4, Stealth +2
**Condition Immunities:** blinded; deafened; exhaustion

---

### Traits

**Needle Defense.** Each time a creature makes a melee attack against a needle lord, it takes 2 piercing damage. A creature can choose to make an attack with disadvantage to avoid this damage.


---

### Actions

**Multiattack.** The nettle lord makes 2 raking vine attacks.

**Needle Volley.** The needle lord makes up to 1d6 needle attacks, but it cannot attack the same target more than twice during its turn.

**Raking Vine.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, and the target is grappled (escape DC 14). Until this grapple ends, the target takes 11 piercing damage at the start of each of its turns. The needle lord has two raking vines, each of which can grapple only one target.

**Needle.** Ranged Weapon Attack: +2 to hit, range 60 ft., one target. *Hit:* 2 (1d4) piercing damage.


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