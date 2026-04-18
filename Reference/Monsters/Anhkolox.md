---
type: pc
race: "Undead"
class:
 - "Anhkolox"
subClass:
 - "CR 9"
cover: "Anhkolox.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/9
  - source/dsotdq
---
###### Anhkolox
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Anhkolox.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 157 (15d12 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 18 | 4 | 14 | 2 |
| **Mod** | +6 | +0 | +4 | -3 | +2 | -4 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** —
**Saving Throws:** Wis +6
**Skills:** Perception +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Unusual Nature.** The anhkolox doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The anhkolox makes two Claw attacks and one Entrapping Rend attack.

**Claw.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or be pushed up to 20 feet in a horizontal direction of the anhkolox's choice.

**Entrapping Rend.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 23 (5d6 + 6) piercing damage, and if the target is a Large or smaller creature, the target must succeed on a DC 18 Strength saving throw or be trapped in the anhkolox's rib cage and grappled (escape DC 18). Until this grapple ends, the target is restrained, and the anhkolox can't use Entrapping Rend on another target.


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