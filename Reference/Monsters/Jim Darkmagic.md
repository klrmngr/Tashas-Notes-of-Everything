---
type: pc
race: "Humanoid (human)"
class:
 - "Jim Darkmagic"
subClass:
 - "CR 5"
cover: "Jim Darkmagic.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ai
---
###### Jim Darkmagic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Jim Darkmagic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 18 | 12 | 14 |
| **Mod** | -1 | +2 | +0 | +4 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common
**Saving Throws:** Int +7, Wis +4
**Skills:** Acrobatics +5, Animal Handling +4, Arcana +7, History +7, Performance +5

---

### Traits

**Special Equipment.** Jim carries a wand of wonder.

**Benign Transportation (Recharges after Jim Casts a Conjuration Spell of 1st Level or Higher).** As a bonus action, Jim teleports up to 30 feet to a space he can see. The space must be unoccupied or occupied by a willing Small or Medium creature. If the latter, Jim and the willing creature both teleport, swapping places.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Minor Conjuration.** Jim conjures an inanimate object, no larger than 3 feet on a side and no more than 10 pounds, in his hand or on the ground in an unoccupied space he can see within 10 feet of him. The object is visibly magical, radiating dim light out to 5 feet. It disappears if it takes any damage, after 1 hour, or when Jim uses this feature again.


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