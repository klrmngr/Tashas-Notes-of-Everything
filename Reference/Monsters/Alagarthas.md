---
type: pc
race: "Humanoid (elf)"
class:
 - "Alagarthas"
subClass:
 - "CR 3"
cover: "Alagarthas.png"
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
###### Alagarthas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Alagarthas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 11 | 11 | 15 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish
**Saving Throws:** Con +4, Wis +2

---

### Traits

**Brave.** Alagarthas has advantage on saving throws against being frightened.

**Fey Ancestry.** Alagarthas has advantage on saving throws against being charmed, and magic can't put him to sleep.


---

### Actions

**Multiattack.** Alagarthas makes two melee attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 bludgeoning damage.

**Leadership (Recharges after a Short or Long Rest).** For 1 minute, Alagarthas can utter a special command or warning whenever a nonhostile creature that it can see within 30 feet of it makes an attack roll or a saving throw. The creature can add a d4 to its roll provided it can hear and understand him. A creature can benefit from only one Leadership die at a time. This effect ends if Alagarthas is incapacitated.


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