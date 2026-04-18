---
type: pc
race: "Aberration"
class:
 - "Mr. Dory"
subClass:
 - "CR 10"
cover: "Mr. Dory.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/10
  - source/gos
---
###### Mr. Dory
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Mr. Dory.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (studded leather, shield) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 20 | 19 | 14 | 14 | 16 |
| **Mod** | +1 | +5 | +4 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Abyssal, Common, Deep Speech, telepathy 60 ft.
**Saving Throws:** Con +8, Wis +6
**Skills:** Athletics +5, Perception +6, Stealth +9
**Damage Immunities:** necrotic

---

### Traits

**Magic Resistance.** Mr. Dory has advantage on saving throws against spells and other magical effects.

**Water Dependency.** Mr. Dory takes 6 (1d12) acid damage at the end of every hour he goes without exposure to water.


---

### Actions

**Multiattack.** Mr. Dory makes three attacks with his rapier.

**Rapier.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage and 7 (2d6) necrotic damage.

**Eye of Corruption (Recharge 5–6).** Mr. Dory glares at a creature he can see within 30 feet of him. The target must make a DC 15 Constitution saving throw. On a failed save, it takes 27 (5d10) necrotic damage and 27 (5d10) poison damage and then gains vulnerability to both necrotic and poison damage for 1 minute. On a successful save, it takes half damage and does not gain the vulnerabilities.


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