---
type: pc
race: "Humanoid (human)"
class:
 - "Jalester Silvermane"
subClass:
 - "CR 4"
cover: "Jalester Silvermane.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/wdh
---
###### Jalester Silvermane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Jalester Silvermane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (chain mail, Badge of the Watch) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 13 | 12 | 14 | 13 |
| **Mod** | +2 | +2 | +1 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Elvish
**Saving Throws:** Str +4, Con +3
**Skills:** Athletics +4, Survival +4

---

### Traits

**Special Equipment.** Jalester carries a badge of the Watch.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, Jalester can regain 16 (1d10 + 11) hit points.


---

### Actions

**Multiattack.** Jalester makes two weapon attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage when used with two hands.

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


---

### Reactions

**Riposte.** When a creature that Jalester can see misses him with a melee attack, he can use his reaction to make a melee weapon attack against that creature. On a hit, the target takes an extra 4 damage from the weapon.


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