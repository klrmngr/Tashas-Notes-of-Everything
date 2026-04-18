---
type: pc
race: "Humanoid (human)"
class:
 - "Thessalar"
subClass:
 - "CR 12"
cover: "Thessalar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/imr
---
###### Thessalar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Thessalar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (breastplate) |
> | :FasHeart: HP | 104 (19d8 + 19) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 13 | 19 | 16 | 16 |
| **Mod** | +0 | +1 | +1 | +4 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Draconic, Elvish, Primordial
**Saving Throws:** Con +5, Int +8, Wis +7
**Skills:** Animal Handling +7, Arcana +8, Insight +7, Medicine +7
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Special Equipment.** Thessalar wields a +1 dagger coated with thessaltoxin poison (see appendix C).

**Alchemical Homunculus.** Thessalar is accompanied by his [[Thessalar's homunculus]]. If the mending spell is cast on it, the homunculus regains 2d6 hit points.

**Healing Toxicity.** Any magic item that restores hit points and can be applied to a piercing or slashing weapon (a potion, an ointment, and so forth) causes a hit with that weapon to deal extra damage to Thessalar equal to the amount the item would normally heal.

**Greater Restoration (1/Day).** Thessalar can cast greater restoration if he has access to alchemical supplies.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage, and the target must succeed on a DC 15 Constitution saving throw. On a failed save, the target is affected as if by the polymorph spell, transforming into a random type=beast or a creature it has seen within the last 24 hours (as chosen by the DM). This effect lasts until the target finishes a long rest.


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