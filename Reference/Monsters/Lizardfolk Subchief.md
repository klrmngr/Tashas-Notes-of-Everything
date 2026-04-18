---
type: pc
race: "Humanoid (lizardfolk)"
class:
 - "Lizardfolk Subchief"
subClass:
 - "CR 3"
cover: "Lizardfolk Subchief.png"
campaign:
locations:
tags:
  - race/lizardfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/gos
---
###### Lizardfolk Subchief
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Lizardfolk Subchief.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (lizardfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (lizardfolk) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 10 | 16 | 12 |
| **Mod** | +2 | +1 | +2 | +0 | +3 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Draconic
**Saving Throws:** Wis +5
**Skills:** Athletics +4, Perception +5, Survival +5

---

### Traits

**Hold Breath.** The subchief can hold its breath for 15 minutes.


---

### Actions

**Tooth Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Jaws of Semuanya (Recharge 5–6).** The subchief invokes the primal magic of Semuanya, summoning a spectral maw around a target it can see within 60 feet of it. The target must make a DC 13 Dexterity saving throw, taking 22 (5d8) piercing damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw is also frightened until the end of its next turn.


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