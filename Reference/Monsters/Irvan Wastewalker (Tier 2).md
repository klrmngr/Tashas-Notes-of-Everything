---
type: pc
race: "Humanoid (human)"
class:
 - "Irvan Wastewalker (Tier 2)"
subClass:
 - "CR 5"
cover: "Irvan Wastewalker (Tier 2).png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/crcotn
---
###### Irvan Wastewalker (Tier 2)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Irvan Wastewalker (Tier 2).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 14 | 14 | 14 |
| **Mod** | +0 | +3 | +1 | +2 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Goblin
**Saving Throws:** Dex +6, Con +4
**Skills:** Acrobatics +6, Deception +5, Stealth +9, Survival +5

---

### Traits

**Fortitude (Recharges after a Short or Long Rest).** If damage reduces Irvan to 0 hit points, he can make a Constitution saving throw with a DC equal to 5 + the damage taken. On a successful save, Irvan drops to 1 hit point instead.


---

### Actions

**Multiattack.** Irvan makes two Dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 14 (4d6) poison damage.


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