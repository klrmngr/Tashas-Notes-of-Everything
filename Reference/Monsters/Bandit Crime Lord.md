---
type: pc
race: "Humanoid"
class:
 - "Bandit Crime Lord"
subClass:
 - "CR 11"
cover: "Bandit Crime Lord.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/11
  - source/xmm
---
###### Bandit Crime Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bandit Crime Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 169 (26d8 + 52) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 20 | 14 | 18 | 14 | 15 |
| **Mod** | +0 | +5 | +2 | +4 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +9, Con +6
**Skills:** Acrobatics +9, Perception +10, Stealth +13

---

### Traits

**Evasion.** If the bandit is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the bandit instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the Incapacitated condition.


---

### Actions

**Multiattack.** The bandit makes three attacks, using Scimitar or Pistol in any combination.

**Scimitar.** m +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 14 (4d6) Poison damage.

**Pistol.** r +9, range 30/90 ft. *Hit:* 10 (1d10 + 5) Piercing damage plus 14 (4d6) Poison damage.


---

### Bonus Actions

**Deadly Aim.** The bandit gives itself Advantage on the next attack roll it makes during the current turn. If that attack hits, the target takes an extra 28 (8d6) Poison damage.


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