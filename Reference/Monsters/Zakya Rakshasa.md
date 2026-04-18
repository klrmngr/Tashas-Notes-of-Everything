---
type: pc
race: "Fiend"
class:
 - "Zakya Rakshasa"
subClass:
 - "CR 5"
cover: "Zakya Rakshasa.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/erlw
---
###### Zakya Rakshasa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Zakya Rakshasa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (scale mail, shield) |
> | :FasHeart: HP | 59 (7d8 + 28) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 12 | 13 | 11 |
| **Mod** | +4 | +2 | +4 | +1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Infernal
**Skills:** Athletics +7, Perception +4
**Damage Vulnerabilities:** piercing from magic weapons wielded by good creatures
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Limited Magic Immunity.** The rakshasa can't be affected or detected by spells of 1st level or lower unless it wishes to be. It has advantage on saving throws against all other spells and magical effects.

**Magic Weapons.** The rakshasa's weapon attacks are magical.

**Martial Prowess (1/Turn).** When the rakshasa hits a creature with a melee weapon attack, the attack deals an extra 11 (2d10) damage of the weapon's type, and the creature must make a DC 15 Strength saving throw. On a failure, the rakshasa can push the creature up to 10 feet away from it, knock the creature prone, or make the creature drop one item it is holding of the rakshasa's choice.


---

### Actions

**Multiattack.** The rakshasa makes three melee weapon attacks. Alternatively, it can make two ranged attacks with its javelins.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Javelin.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


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