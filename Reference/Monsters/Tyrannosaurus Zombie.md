---
type: pc
race: "Undead"
class:
 - "Tyrannosaurus Zombie"
subClass:
 - "CR 8"
cover: "Tyrannosaurus Zombie.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/8
  - source/toa
---
###### Tyrannosaurus Zombie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Tyrannosaurus Zombie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 136 (13d12 + 52) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 6 | 19 | 1 | 3 | 5 |
| **Mod** | +7 | -2 | +4 | -5 | -4 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 6
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Disgorge Zombie.** As a bonus action, the tyrannosaurus zombie can disgorge a normal zombie, which appears in an unoccupied space within 10 feet of it. The disgorged zombie acts on its own initiative count. After a zombie is disgorged, roll a d6. On a roll of 1, the tyrannosaurus zombie runs out of zombies to disgorge and loses this trait. If the tyrannosaurus zombie still has this trait when it dies, 1d4 normal zombies erupt from its corpse at the start of its next turn. These zombies act on their own initiative count.

**Undead Fortitude.** If damage reduces the tyrannosaurus zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.


---

### Actions

**Multiattack.** The tyrannosaurus zombie makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

**Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 33 (4d12 + 7) piercing damage. If the target is a Medium or smaller creature, it is grappled (escape DC 17). Until this grapple ends, the target is restrained and the tyrannosaurus zombie can't bite another target or disgorge zombies.

**Tail.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage.


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