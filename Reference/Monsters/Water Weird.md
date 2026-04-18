---
type: pc
race: "Elemental"
class:
 - "Water Weird"
subClass:
 - "CR 3"
cover: "Water Weird.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/mm
---
###### Water Weird
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Water Weird.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 58 (9d10 + 9) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 13 | 11 | 10 | 10 |
| **Mod** | +3 | +3 | +1 | +0 | +0 | +0 |

**Speed:** 0 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 10
**Languages:** understands Aquan but doesn't speak
**Damage Resistances:** fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; poisoned; restrained; prone; unconscious

---

### Traits

**Invisible in Water.** The water weird is invisible while fully immersed in water.

**Water Bound.** The water weird dies if it leaves the water to which it is bound or if that water is destroyed.


---

### Actions

**Constrict.** Melee Weapon Attack: +5 to hit, reach 10 ft., one creature. *Hit:* 13 (3d6 + 3) bludgeoning damage. If the target is Medium or smaller, it is grappled (escape DC 13) and pulled 5 feet toward the water weird. Until this grapple ends, the target is restrained, the water weird tries to drown it, and the water weird can't constrict another target.


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