---
type: pc
race: "Undead"
class:
 - "Sephek Kaltro"
subClass:
 - "CR 3"
cover: "Sephek Kaltro.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/idrotf
---
###### Sephek Kaltro
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Sephek Kaltro.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 11 | 16 | 18 |
| **Mod** | +3 | +2 | +3 | +0 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common
**Skills:** Perception +5, Survival +5
**Damage Immunities:** cold
**Condition Immunities:** charmed; frightened

---

### Traits

**Cold Regeneration.** If the temperature around him is 0 degrees Fahrenheit or lower, Sephek regains 5 hit points at the start of his turn. If he takes fire damage, this trait doesn't function at the start of Sephek's next turn. Sephek dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Sephek attacks twice with a weapon.

**Ice Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if Sephek uses the weapon with two hands, plus 5 (2d4) cold damage.

**Ice Dagger.** Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 5 (2d4) cold damage.


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