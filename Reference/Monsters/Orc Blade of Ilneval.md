---
type: pc
race: "Humanoid (orc)"
class:
 - "Orc Blade of Ilneval"
subClass:
 - "CR 4"
cover: "Orc Blade of Ilneval.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/vgm
---
###### Orc Blade of Ilneval
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Orc Blade of Ilneval.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 11 | 17 | 10 | 12 | 14 |
| **Mod** | +3 | +0 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Orc
**Saving Throws:** Wis +3
**Skills:** Insight +3, Intimidation +4, Perception +3

---

### Traits

**Aggressive.** As a bonus action, the orc can move up to its speed toward a hostile creature that it can see.

**Foe Smiter of Ilneval.** The orc deals an extra die of damage when it hits with a longsword attack (included in the attack).


---

### Actions

**Multiattack.** The orc makes two melee attacks with its longsword or two ranged attacks with its javelins. If Ilneval's Command is available to use, the orc can use it after these attacks.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage, or 14 (2d10 + 3) slashing damage when used with two hands.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Ilneval's Command (Recharge 4–6).** Up to three allied orcs within 120 feet of this orc that can hear it can use their reactions to each make one weapon attack.


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