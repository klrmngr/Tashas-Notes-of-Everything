---
type: pc
race: "Monstrosity"
class:
 - "Swavain Basilisk"
subClass:
 - "CR 7"
cover: "Swavain Basilisk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/7
  - source/egw
---
###### Swavain Basilisk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Swavain Basilisk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 85 (10d12 + 20) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 15 | 2 | 8 | 7 |
| **Mod** | +2 | +3 | +2 | -4 | -1 | -2 |

**Speed:** 15 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The basilisk can breathe air and water.

**Petrifying Secretions.** A creature must make a DC 13 Constitution saving throw if it hits the basilisk with a weapon attack while within 5 feet of it or if it starts its turn grappled by the basilisk. Unless the save succeeds, the creature magically begins to turn to stone and is restrained, and it must repeat the saving throw at the end of its next turn. On a successful save, the effect ends. On a failure, the creature is petrified.


---

### Actions

**Multiattack.** The basilisk makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 13 (3d6 + 3) piercing damage plus 10 (3d6) poison damage.

**Tail.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 14 (2d10 + 3) bludgeoning damage. If the target is a Large or smaller creature, it is grappled (escape DC 12).


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