---
type: pc
race: "Humanoid (human)"
class:
 - "Rath Modar"
subClass:
 - "CR 6"
cover: "Rath Modar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/hotdq
---
###### Rath Modar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Rath Modar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 18 | 14 | 10 |
| **Mod** | +0 | +3 | +2 | +4 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic, Infernal, Primordial, Thayan
**Saving Throws:** Int +7, Wis +5
**Skills:** Arcana +7, Deception +3, Insight +5, Stealth +6

---

### Traits

**Special Equipment.** Rath has a staff of fire, and scrolls of dimension door, feather fall, and fireball.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) bludgeoning damage.


---

### Reactions

**Illusory Self (Recharges on a Short or Long Rest).** When a creature Rath can see makes an attack roll against him, he can interpose an illusory duplicate between the attacker and him. The attack automatically misses Rath, then the illusion dissipates.


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