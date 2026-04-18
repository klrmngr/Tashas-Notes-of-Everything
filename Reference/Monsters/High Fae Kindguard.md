---
type: pc
race: "Fey"
class:
 - "High Fae Kindguard"
subClass:
 - "CR 12"
cover: "High Fae Kindguard.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/12
  - source/mcv4ec
---
###### High Fae Kindguard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[High Fae Kindguard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 23 | 15 | 14 | 17 | 13 |
| **Mod** | +6 | +6 | +2 | +2 | +3 | +1 |

**Speed:** 40 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Common, Sylvan
**Saving Throws:** Str +10, Dex +10
**Skills:** Acrobatics +10, Athletics +10, Perception +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Evasion.** If the high fae is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw and only half damage if it fails, provided it doesn't have the incapacitated condition.

**Magic Resistance.** The high fae has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The high fae makes two Fae Claymore attacks and uses Tripping Feint.

**Fae Claymore.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 20 (4d6 + 6) force damage, and the target's speed is reduced by 10 feet, to a minimum speed of 5 feet. The reduction lasts until the start of the high fae's next turn.

**Tripping Feint.** The high fae targets one Large or smaller creature it can see within 10 feet of itself. The target must succeed on a DC 18 Dexterity saving throw or have the prone condition.


---

### Bonus Actions

**Darting Flight.** The high fae moves up to its speed. This movement doesn't provoke opportunity attacks.


---

### Reactions

**Parry and Riposte.** The high fae adds 4 to its AC against one melee attack roll that would hit it, provided it can see the attacker. After the attack hits or misses, the high fae then makes one Fae Claymore attack against the attacker.


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