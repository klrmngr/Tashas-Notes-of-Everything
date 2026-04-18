---
type: pc
race: "Aberration"
class:
 - "Greater Shadow Horror"
subClass:
 - "CR 12"
cover: "Greater Shadow Horror.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/12
  - source/aitfr-thp
---
###### Greater Shadow Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-THP
___

> [!infobox|no-t right]
> ![[Greater Shadow Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 170 (20d12 + 40) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | AitFR-THP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 2 | 17 | 18 |
| **Mod** | +2 | +3 | +2 | -4 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** —
**Skills:** Perception +7, Stealth +11
**Damage Vulnerabilities:** radiant
**Condition Immunities:** frightened

---

### Traits

**Incorporeal Movement.** The horror can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Legendary Resistance (2/Day).** If the horror fails a saving throw, it can choose to succeed instead.

**Shadow Stealth.** While in dim light or darkness, the horror can take the Hide action as a bonus action.

**Shadow Stride.** As a bonus action, the horror can step into a shadow within 5 feet of it and magically appear in an unoccupied space within 5 feet of a second shadow that is up to 60 feet away. Both shadows must be cast by a Medium or larger creature or object.

**Sunlight Sensitivity.** While in sunlight, the horror has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The horror makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 21 (4d8 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 17 (4d6 + 3) slashing damage, and the target must succeed on a DC 16 Wisdom saving throw or be frightened of the horror until the end of the target's next turn.

**Lashing Shadows (Recharge 5–6).** Each creature within 60 feet of the horror, except other horrors, must succeed on a DC 16 Dexterity saving throw or take 36 (8d8) necrotic damage.


---

### Legendary Actions

### 

**Claw.** The horror makes a weapon attack.

**Glide.** The horror moves up to 20 feet without provoking opportunity attacks.

**Frighten Foe (Costs 2 Actions).** The horror targets one enemy it can see within 30 feet of it. If the target can see and hear it, the target must succeed on a DC 16 Wisdom saving throw or be frightened until the end of horror's next turn.


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