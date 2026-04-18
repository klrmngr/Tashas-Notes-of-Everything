---
type: pc
race: "Humanoid (kuo-toa)"
class:
 - "Kuo-toa Whip"
subClass:
 - "CR 1"
cover: "Kuo-toa Whip.png"
campaign:
locations:
tags:
  - race/kuo-toa
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/mm
---
###### Kuo-toa Whip
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Kuo-toa Whip.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (kuo-toa) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (kuo-toa) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 12 | 14 | 11 |
| **Mod** | +2 | +0 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Undercommon
**Skills:** Perception +6, Religion +5

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Otherworldly Perception.** The kuo-toa can sense the presence of any creature within 30 feet of it that is invisible or on the Ethereal Plane. It can pinpoint such a creature that is moving.

**Slippery.** The kuo-toa has advantage on ability checks and saving throws made to escape a grapple.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The kuo-toa makes two attacks: one with its bite and one with its pincer staff.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Pincer Staff.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 14). Until this grapple ends, the kuo-toa can't use its pincer staff on another target.


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