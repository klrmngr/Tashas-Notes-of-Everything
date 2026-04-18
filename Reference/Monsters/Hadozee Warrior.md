---
type: pc
race: "Humanoid"
class:
 - "Hadozee Warrior"
subClass:
 - "CR 1/2"
cover: "Hadozee Warrior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/bam
---
###### Hadozee Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Hadozee Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 13 | 10 | 13 | 12 |
| **Mod** | +0 | +3 | +1 | +0 | +1 | +1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Hadozee
**Saving Throws:** Dex +5, Con +3
**Skills:** Perception +3, Stealth +5, Survival +5

---

### Traits

**Glide.** If it isn't incapacitated or wearing heavy armor, the hadozee can extend its skin membranes to move up to 5 feet horizontally for every 1 foot it descends in the air.


---

### Actions

**Multiattack.** The hadozee makes two Shortsword attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Light Crossbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage.


---

### Reactions

**Safe Descent.** When it would take damage from a fall, the hadozee extends its skin membranes to reduce the fall's damage to 0, provided it isn't wearing heavy armor.

**Uncanny Dodge.** The hadozee halves the damage that it takes from an attack that hits it, provided it can see the attacker.


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