---
type: pc
race: "Humanoid (orc)"
class:
 - "Zarak"
subClass:
 - "CR 2"
cover: "Zarak.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wbtw
---
###### Zarak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Zarak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 16 | 11 | 15 | 6 |
| **Mod** | +1 | +3 | +3 | +0 | +2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60, passive Perception 16
**Languages:** Common, Orc
**Saving Throws:** Dex +5, Int +2
**Skills:** Acrobatics +7, Insight +6, Perception +6, Stealth +7

---

### Traits

**Special Equipment.** Zarak carries a potion of invisibility.


---

### Actions

**Multiattack.** Zarak makes two Dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, plus an extra 5 (2d4) piercing damage if the target is a creature and Zarak has at least 18 hit points.

**Garrote.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Humanoid. *Hit:* 8 (2d4 + 3) slashing damage, and the target is grappled (escape DC 11). Until this grapple ends, the target takes 8 (2d4 + 3) slashing damage at the start of each of its turns, and Zarak can't grapple another creature or use Assassin's Whim.


---

### Bonus Actions

**Assassin's Whim.** Zarak takes the Dash, Disengage, or Hide action.


---

### Reactions

**Uncanny Dodge.** Zarak halves the damage he takes from an attack made against him, provided he can see the attacker.


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