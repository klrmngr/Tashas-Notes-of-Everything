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
  - source/mpmm
---
###### Githzerai Anarch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Githzerai Anarch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 20 (psychic defense) |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Legendary Resistance (3/Day).** If the githzerai fails a saving throw, it can choose to succeed instead.

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage plus 18 (4d8) psychic damage.


---

### Legendary Actions

### 

**Strike.** The githzerai makes one Unarmed Strike attack.

**Teleport.** The githzerai teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 30 feet of it.

**Change Gravity (Costs 3 Actions).** The githzerai casts the reverse gravity spell, using Wisdom as the spellcasting ability. The spell has the normal effect, except that the githzerai can orient the area in any direction and creatures and objects fall toward the end of the area.


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