---
type: pc
race: "Humanoid (human)"
class:
 - "Reaper of Bhaal"
subClass:
 - "CR 2"
cover: "Reaper of Bhaal.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/bgdia
---
###### Reaper of Bhaal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Reaper of Bhaal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 20 | 13 | 15 | 12 | 16 |
| **Mod** | +0 | +5 | +1 | +2 | +1 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Skills:** Intimidation +5, Perception +3, Persuasion +5, Stealth +9

---

### Traits

**Aura of Murder.** As long as the reaper is not incapacitated, hostile creatures within 5 feet of it gain vulnerability to piercing damage unless they have resistance or immunity to such damage.


---

### Actions

**Multiattack.** The reaper makes two dagger attacks and uses Shroud Self.

**Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.

**Shroud Self.** The reaper magically turns invisible until the start of its next turn. This invisibility ends if the reaper makes an attack roll, makes a damage roll, or casts a spell.


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