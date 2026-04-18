---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Emerald Enclave Scout"
subClass:
 - "CR 1/2"
cover: "Emerald Enclave Scout.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/oota
---
###### Emerald Enclave Scout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Emerald Enclave Scout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 11 | 13 | 11 |
| **Mod** | +0 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Dwarvish
**Skills:** Nature +4, Perception +5, Stealth +6, Survival +5
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** The scout has advantage on saving throws against poison.

**Keen Hearing and Sight.** The scout has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Multiattack.** The scout makes two melee attacks.

**War Pick.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage.


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