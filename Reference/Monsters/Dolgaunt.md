---
type: pc
race: "Aberration"
class:
 - "Dolgaunt"
subClass:
 - "CR 3"
cover: "Dolgaunt.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/erlw
---
###### Dolgaunt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Dolgaunt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (Unarmored Defense) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 12 | 13 | 14 | 11 |
| **Mod** | +2 | +4 | +1 | +1 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 14
**Languages:** Deep Speech, Goblin
**Skills:** Acrobatics +6, Perception +4, Stealth +6
**Condition Immunities:** blinded

---

### Traits

**Evasion.** If the dolgaunt is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the dolgaunt instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. It can't use this trait if it's incapacitated.

**Unarmored Defense.** While the dolgaunt is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The dolgaunt makes two tentacle attacks and two unarmed strikes. Up to two tentacle attacks can be replaced by Vitality Drain.

**Tentacle.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage. The target is grappled (escape DC 12) if it is a Large or smaller creature. Until this grapple ends, the dolgaunt can't use the same tentacle on another target. The dolgaunt has two tentacles.

**Unarmed Strike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) bludgeoning damage.

**Vitality Drain.** One creature grappled by a tentacle of the dolgaunt must make a DC 11 Constitution saving throw. On a failed save, the target takes 9 (2d8) necrotic damage, and the dolgaunt regains a number of hit points equal to half the necrotic damage taken.


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