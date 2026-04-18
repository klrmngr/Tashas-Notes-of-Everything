---
type: pc
race: "Humanoid (lizardfolk)"
class:
 - "Lizardfolk Scaleshield"
subClass:
 - "CR 1"
cover: "Lizardfolk Scaleshield.png"
campaign:
locations:
tags:
  - race/lizardfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/gos
---
###### Lizardfolk Scaleshield
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Lizardfolk Scaleshield.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (lizardfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (scale mail, shield) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (lizardfolk) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 14 | 7 | 12 | 7 |
| **Mod** | +2 | +0 | +2 | -2 | +1 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Draconic
**Skills:** Athletics +4, Perception +3, Survival +5

---

### Traits

**Hold Breath.** The scaleshield can hold its breath for 15 minutes.


---

### Actions

**Multiattack.** The scaleshield makes two melee attacks, each one with a different weapon.

**Morningstar.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Spiked Shield.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


---

### Reactions

**Shield Block.** If an ally within 5 feet of the scaleshield is hit by an attack, the scaleshield can reduce that attack's damage by half.


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