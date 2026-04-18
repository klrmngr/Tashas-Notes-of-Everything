---
type: pc
race: "Ooze"
class:
 - "Ooze-Folk"
subClass:
 - "CR 1/2"
cover: "Ooze-Folk.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/1-2
  - source/llk
---
###### Ooze-Folk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Laboratory of Kwalish
___

> [!infobox|no-t right]
> ![[Ooze-Folk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 (natural armor) |
> | :FasHeart: HP | 19 (2d8 + 10) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Lost Laboratory of Kwalish |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 3 | 20 | 1 | 6 | 1 |
| **Mod** | +2 | -4 | +5 | -5 | -2 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 8
**Languages:** —
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; prone

---

### Traits

**Transparent.** Even when an ooze-folk is in plain sight, it takes a DC 12 Wisdom (Perception) check to spot an ooze-folk that has neither moved nor attacked. A creature that tries to enter the ooze-folk's space while unaware of the ooze-folk is surprised by the ooze-folk.

**Fragile Bones.** For each 5 damage it takes, the ooze-folk's walking speed is reduced by 5 feet.


---

### Actions

**Multiattack.** The ooze folk makes one glass longsword attack and one pseudopod attack.

**Glass Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 6 (1d8 + 2) slashing damage. If a 1 is rolled on an attack roll with a glass longsword, it shatters and can no longer be used.

**Pseudopod.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 5 (1d6 + 2) acid damage. 


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