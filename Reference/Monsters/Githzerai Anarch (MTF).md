---
type: pc
race: "Humanoid (gith)"
class:
 - "Githzerai Anarch"
subClass:
 - "CR 16"
cover: "Githzerai Anarch.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/16
  - source/mtf
---
###### Githzerai Anarch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Githzerai Anarch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 21 | 18 | 18 | 20 | 14 |
| **Mod** | +3 | +5 | +4 | +4 | +5 | +2 |

**Speed:** 30 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Gith
**Saving Throws:** Str +8, Dex +10, Int +9, Wis +10
**Skills:** Arcana +9, Insight +10, Perception +10

---

### Traits

**Psychic Defense.** While the anarch is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The anarch makes three unarmed strikes.

**Unarmed Strike.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) bludgeoning damage plus 18 (4d8) psychic damage.


---

### Legendary Actions

### 

**Strike.** The anarch makes one unarmed strike.

**Teleport.** The anarch magically teleports, along with any equipment it is wearing and carrying, to an unoccupied space it can see within 30 feet of it.

**Change Gravity (Costs 3 Actions).** The anarch casts the reverse gravity spell. The spell has the normal effect, except that the anarch can orient the area in any direction and creatures and objects fall toward the end of the area.


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