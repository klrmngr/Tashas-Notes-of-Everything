---
type: pc
race: "Celestial"
class:
 - "Fensir Devourer"
subClass:
 - "CR 8"
cover: "Fensir Devourer.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/huge
  - cr/8
  - source/bgg
---
###### Fensir Devourer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fensir Devourer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Celestial |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 21 | 10 | 14 | 11 |
| **Mod** | +5 | +0 | +5 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** Common, Giant
**Skills:** Perception +8, Survival +8

---

### Traits

**Death Curse.** When the fensir starts its turn with 0 hit points and doesn't regenerate, it releases a curse on those around it. Each creature within 30 feet of the fensir when it dies must succeed on a DC 13 Charisma saving throw or be cursed for the next 24 hours.
While cursed in this way, an affected creature gains no benefit from finishing a short or long rest. At the end of every hour, the creature must succeed on a DC 13 Charisma saving throw or take 11 (2d10) psychic damage.

**Regeneration.** The fensir regains 10 hit points at the start of its turn if it isn't in sunlight. If the fensir takes acid or fire damage, this trait doesn't function at the start of the fensir's next turn. The fensir dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Sunlight Hypersensitivity.** When the fensir starts its turn in sunlight, it must succeed on a DC 15 Constitution saving throw or have the petrified condition until the fensir is no longer in sunlight.


---

### Actions

**Multiattack.** The fensir makes two attacks, using Rend, Boulder, or a combination of them.

**Rend.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) slashing damage.

**Boulder.** Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. *Hit:* 18 (2d12 + 5) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 16 Strength saving throw or have the prone condition. After the fensir throws the boulder, roll a d6; on a roll of 4 or lower, the fensir has no more boulders to throw.


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