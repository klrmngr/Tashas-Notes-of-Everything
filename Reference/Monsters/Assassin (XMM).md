---
type: pc
race: "Humanoid"
class:
 - "Assassin"
subClass:
 - "CR 8"
cover: "Assassin.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Assassin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Assassin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 16 | 11 | 10 |
| **Mod** | +0 | +4 | +2 | +3 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +7, Int +6
**Skills:** Acrobatics +7, Perception +6, Stealth +10
**Damage Resistances:** poison

---

### Traits

**Evasion.** If the assassin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the assassin instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the Incapacitated condition.


---

### Actions

**Multiattack.** The assassin makes three attacks, using Shortsword or Light Crossbow in any combination.

**Shortsword.** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage plus 17 (5d6) Poison damage, and the target has the Poisoned condition until the start of the assassin's next turn.

**Light Crossbow.** r +7, range 80/320 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 21 (6d6) Poison damage.


---

### Bonus Actions

**Cunning Action.** The assassin takes the Dash, Disengage, or Hide action.


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