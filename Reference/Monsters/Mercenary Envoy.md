---
type: pc
race: "Humanoid"
class:
 - "Mercenary Envoy"
subClass:
 - "CR 1"
cover: "Mercenary Envoy.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/aitfr-fcd
---
###### Mercenary Envoy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-FCD
___

> [!infobox|no-t right]
> ![[Mercenary Envoy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | AitFR-FCD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 15 | 10 | 12 | 9 |
| **Mod** | +2 | +2 | +2 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Saving Throws:** Str +4, Con +4
**Skills:** Athletics +4, Perception +3

---

### Traits

**Inspired Courage.** The mercenary has advantage on savings throws against being charmed, frightened, grappled, or restrained while within 5 feet of at least one ally.

**Martial Advantage.** Once per turn, the mercenary can deal an extra 7 (2d6) damage to a creature it hits with a weapon attack if that creature is within 5 feet of an ally of the mercenary that isn't incapacitated.


---

### Actions

**Multiattack.** The mercenary makes two longsword attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +4 to hit, range
100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.


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