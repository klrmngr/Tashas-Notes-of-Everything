---
type: pc
race: "Undead"
class:
 - "Undying Soldier"
subClass:
 - "CR 2"
cover: "Undying Soldier.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/2
  - source/erlw
---
###### Undying Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Undying Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (breastplate, shield) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 14 | 11 | 13 | 14 |
| **Mod** | +3 | +1 | +2 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Skills:** Athletics +5, History +4, Perception +3, Religion +4
**Damage Vulnerabilities:** necrotic
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Illumination.** The soldier magically sheds bright light in a 10-foot radius and dim light for an additional 10 feet. The soldier can extinguish or restore this light as a bonus action.

**Turn Resistance.** The soldier has advantage on saving throws against any effect that turns undead.


---

### Actions

**Multiattack.** The soldier makes two spear attacks.

**Spear.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage or 7 (1d8 + 3) piercing damage if used with two hands to make a melee attack, plus 9 (2d8) radiant damage if the target is a fiend or undead.


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