---
type: pc
race: "Giant"
class:
 - "Irda Seeker"
subClass:
 - "CR 1"
cover: "Irda Seeker.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/medium
  - cr/1
  - source/mcv2dc
---
###### Irda Seeker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Irda Seeker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Giant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 11 | 14 | 16 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., truesight 5 ft., passive Perception 16
**Languages:** Common, Giant, Sylvan
**Saving Throws:** Dex +4, Cha +5
**Skills:** Insight +6, Perception +6, Stealth +4

---

### Actions

**Multiattack.** The seeker uses Augment Physicality, if available, and makes two Crystal Blade attacks.

**Crystal Blade.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) force damage, plus 7 (2d6) force damage if the seeker is Large.

**Augment Physicality (1/Day).** For 1 minute, the seeker magically heightens its physical ability and increases in size, along with anything it is wearing or carrying. While augmented, the seeker is Large, and makes Strength and Dexterity saving throws with advantage. If the seeker lacks the room to become Large, it attains the maximum size possible in the space available.

**Change Shape (1/Day).** The seeker magically transforms to look and feel like a Medium Humanoid it has seen. Any equipment the seeker is wearing or carrying isn't transformed, and the seeker's statistics don't change. The seeker reverts to its true form if the seeker is reduced to 0 hit points or if the seeker uses an action to end the transformation.


---

### Bonus Actions

**Veil Walk (Recharge 4–6).** The seeker, along with any equipment it is wearing or carrying, turns invisible and teleports to an unoccupied space it can see within 30 feet of itself. The seeker remains invisible until the start of its next turn or until immediately after the seeker makes an attack roll, whichever comes first.


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