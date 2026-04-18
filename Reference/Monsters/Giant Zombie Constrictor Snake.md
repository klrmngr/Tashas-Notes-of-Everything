---
type: pc
race: "Undead"
class:
 - "Giant Zombie Constrictor Snake"
subClass:
 - "CR 8"
cover: "Giant Zombie Constrictor Snake.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/8
  - source/aitfr-dn
---
###### Giant Zombie Constrictor Snake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-DN
___

> [!infobox|no-t right]
> ![[Giant Zombie Constrictor Snake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 187 (22d12 + 44) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | AitFR-DN |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 14 | 1 | 15 | 4 |
| **Mod** | +4 | +3 | +2 | -5 | +2 | -3 |

**Speed:** 30 ft., climb 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 15 ft., darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +6
**Damage Vulnerabilities:** poison

---

### Traits

**Sunlight Vulnerability.** While in sunlight, the snake has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight. When the snake begins its turn in sunlight, it immediately suffers 10 radiant damage.

**Undead Fortitude.** If damage reduces the snake to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the snake drops to 1 hit point instead.


---

### Actions

**Multiattack.** The snake makes two attacks: one with its bite and one with a constrict attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 17 (3d8 + 4) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 17 (5d6) poison damage on a failed save, or half as much damage on a successful one.

**Constrict.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 17 (3d8 + 4) bludgeoning damage, and the target is grappled (escape DC 16). Until this grapple ends, the creature is restrained and the snake cannot constrict another target.


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