---
type: pc
race: "Humanoid (human)"
class:
 - "Hellenrae"
subClass:
 - "CR 5"
cover: "Hellenrae.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/pota
---
###### Hellenrae
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Hellenrae.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 10 | 15 | 13 |
| **Mod** | +1 | +4 | +2 | +0 | +2 | +1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 15
**Languages:** Common, Terran
**Skills:** Acrobatics +7, Athletics +4, Insight +5, Perception +5
**Damage Immunities:** poison
**Condition Immunities:** blinded; poisoned

---

### Traits

**Evasion.** If Hellenrae is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, she instead takes no damage if she succeeds on the saving throw, and only half damage if she fails.

**Stunning Strike (Recharge 5–6).** When Hellenrae hits a target with a melee weapon attack, the target must succeed on a DC 13 Constitution saving throw or be stunned until the end of Hellenrae's next turn.

**Unarmored Defense.** While Hellenrae is wearing no armor and wielding no shield, her AC includes her Wisdom modifier.

**Unarmored Movement.** While Hellenrae is wearing no armor and wielding no shield, her speed increases by 20 feet (included in her speed).


---

### Actions

**Multiattack.** Hellenrae makes three melee attacks.

**Unarmed Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage.


---

### Reactions

**Parry and Counter.** Hellenrae adds 3 to her AC against one melee or ranged weapon attack that would hit her. To do so, she must be able to sense the attacker with her blindsight. If the attack misses, Hellenrae can make one melee attack against the attacker if it is within her reach.


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