---
type: pc
race: "Humanoid (elf, shadar-kai)"
class:
 - "Mister Light"
subClass:
 - "CR 3"
cover: "Mister Light.png"
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
###### Mister Light
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Mister Light.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf, shadar-kai) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 77 (14d8 + 14) |
> | :FasUserGroup: Race | Humanoid (elf, shadar-kai) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 12 | 13 | 17 |
| **Mod** | +0 | +3 | +1 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Dex +5, Cha +5
**Skills:** Perception +3, Performance +5, Sleight Of Hand +5
**Damage Vulnerabilities:** lightning
**Damage Resistances:** necrotic
**Condition Immunities:** blinded; deafened; petrified; stunned

---

### Traits

**Fey Ancestry.** Light has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Special Equipment.** Light carries and is attuned to the Witchlight vane. In Light's hands, the vane is a finesse weapon.


---

### Actions

**Multiattack.** Light makes two Witchlight vane attacks.

**Witchlight Vane.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 4 (1d8) radiant damage.


---

### Bonus Actions

**Blessing of the Raven Queen (1/Day).** Light magically teleports, along with any equipment he is wearing or carrying, up to 30 feet to an unoccupied space he can see. Until the start of his next turn, he appears ghostly and gains resistance to all damage.


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