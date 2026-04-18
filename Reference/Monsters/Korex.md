---
type: pc
race: "Humanoid (elf)"
class:
 - "Korex"
subClass:
 - "CR 2"
cover: "Korex.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wtthc
---
###### Korex
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Korex.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 52 (8d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 14 | 8 | 12 | 15 |
| **Mod** | +1 | +3 | +2 | -1 | +1 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Common, Elvish
**Skills:** Perception +3, Performance +4, Stealth +5
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Sewer Speech.** Korex can comprehend and verbally communicate with Monstrosities.


---

### Actions

**Rancid Knife.** m +5, reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing damage plus 7 (2d6) Poison damage, and the target has the Poisoned condition until the start of Korex's next turn.

**Entrancing Pipes.** wis DC 12, one creature Korex can see within 120 feet.  14 (4d6) Psychic damage, and the target has the Charmed condition until the start of Korex's next turn.  Half damage only.


---

### Bonus Actions

**Skitter.** Korex takes the Dash or Disengage action.


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