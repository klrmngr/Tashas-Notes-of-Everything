---
type: pc
race: "Humanoid (elf, shadar-kai)"
class:
 - "Mister Witch"
subClass:
 - "CR 3"
cover: "Mister Witch.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wbtw
---
###### Mister Witch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Mister Witch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf, shadar-kai) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid (elf, shadar-kai) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 16 | 16 | 13 | 14 |
| **Mod** | +2 | +0 | +3 | +3 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Int +5, Wis +3
**Skills:** Arcana +5, Deception +4, Perception +3
**Damage Resistances:** necrotic

---

### Traits

**Fey Ancestry.** Witch has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Special Equipment.** Witch carries and is attuned to the Witchlight watch.


---

### Actions

**Multiattack.** Witch makes two Cane attacks.

**Cane.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage plus 6 (1d12) necrotic damage.


---

### Bonus Actions

**Blessing of the Raven Queen (1/Day).** Witch magically teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see. Until the start of his next turn, he appears ghostly and gains resistance to all damage.


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