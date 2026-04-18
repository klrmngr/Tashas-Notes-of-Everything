---
type: pc
race: "Humanoid (human)"
class:
 - "Irvan Wastewalker (Tier 3)"
subClass:
 - "CR 8"
cover: "Irvan Wastewalker (Tier 3).png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/crcotn
---
###### Irvan Wastewalker (Tier 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Irvan Wastewalker (Tier 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (studded leather) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 20 | 14 | 16 | 16 | 16 |
| **Mod** | +0 | +5 | +2 | +3 | +3 | +3 |

**Speed:** 40 ft., swim 40 ft. ((see special equipment)) &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Goblin, Orc
**Saving Throws:** Dex +8, Con +5
**Skills:** Acrobatics +8, Deception +9, Stealth +11, Survival +6

---

### Traits

**Fortitude (Recharges after a Short or Long Rest).** If damage reduces Irvan to 0 hit points, he can make a Constitution saving throw with a DC equal to 5 + the damage taken. On a successful save, Irvan drops to 1 hit point instead.

**Special Equipment.** Irvan wears gloves of swimming and climbing and wields a ruidium shortsword (see appendix B). If Irvan rolls a 1 on an attack roll made with the shortsword, he must succeed on a DC 20 Charisma saving throw or gain 1 level of exhaustion.
In addition, Irvan has a magical prosthetic arm. While the arm is attached to him, it functions the same as the body part it is replacing. Irvan can attach or detach the arm as an action, and it can't be removed by anyone else.


---

### Actions

**Multiattack.** Irvan makes one Dagger attack and two Ruidium Shortsword attacks.

**Dagger.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 17 (5d6) poison damage.

**Ruidium Shortsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 7 (2d6) psychic damage.


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