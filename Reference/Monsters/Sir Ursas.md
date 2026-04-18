---
type: pc
race: "Humanoid (human)"
class:
 - "Sir Ursas"
subClass:
 - "CR 5"
cover: "Sir Ursas.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/imr
---
###### Sir Ursas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Sir Ursas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 10 | 12 | 15 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Infernal
**Saving Throws:** Str +7, Dex +5, Con +6
**Skills:** Athletics +10, Intimidation +5
**Damage Resistances:** fire

---

### Traits

**Special Equipment.** Sir Ursas wears a ring of mind shielding and plate armor of fire resistance.

**Brave.** Sir Ursas has advantage on saving throws against being frightened.

**Brute.** A melee weapon deals one extra die of its damage when Sir Ursas hits with it (included in his attack).


---

### Actions

**Multiattack.** Sir Ursas makes three melee attacks or two ranged attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. and range 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack.

**Shield Bash.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage, and if the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.


---

### Reactions

**Parry.** Sir Ursas adds 3 to his AC against one melee attack that would hit him. To do so, he must see the attacker and be wielding a melee weapon.


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