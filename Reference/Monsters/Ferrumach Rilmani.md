---
type: pc
race: "Celestial"
class:
 - "Ferrumach Rilmani"
subClass:
 - "CR 9"
cover: "Ferrumach Rilmani.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/9
  - source/mpp
---
###### Ferrumach Rilmani
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Ferrumach Rilmani.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 18 | 15 | 14 | 10 |
| **Mod** | +4 | +2 | +4 | +2 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** telepathy 120 ft., any two languages
**Saving Throws:** Str +8, Con +8
**Skills:** Athletics +8, Perception +6
**Damage Resistances:** psychic

---

### Traits

**Bladed Edges.** A creature takes 10 (3d6) slashing damage if it starts its turn grappling or being grappled by the ferrumach.

**Skewering Charge.** If the ferrumach moves at least 20 feet in a straight line toward a Large or smaller creature and ends within 5 feet of it, that creature must succeed on a DC 16 Strength saving throw or have the grappled condition (escape DC 18) and take 10 (3d6) piercing damage.


---

### Actions

**Multiattack.** The ferrumach makes three Sharpened Limb or Bolt attacks.

**Sharpened Limb.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) slashing damage plus 11 (2d10) psychic damage.

**Bolt.** Ranged Weapon Attack: +8 to hit, range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 11 (2d10) psychic damage.


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