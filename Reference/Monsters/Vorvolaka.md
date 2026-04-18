---
type: pc
race: "Undead"
class:
 - "Vorvolaka"
subClass:
 - "CR 14"
cover: "Vorvolaka.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/14
  - source/coa
---
###### Vorvolaka
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Vorvolaka.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 190 (20d8 + 100) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 19 | 21 | 8 | 13 | 16 |
| **Mod** | +2 | +4 | +5 | -1 | +1 | +3 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** the languages it knew in life
**Saving Throws:** Con +10, Wis +6
**Skills:** Insight +6, Perception +11, Religion +4, Survival +6
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; exhaustion; paralyzed

---

### Traits

**Fear Aura.** Any hostile creature that starts its turn within 20 feet of the vorvolaka must succeed on a DC 18 Wisdom saving throw or have frightened condition until the start of the creature's next turn. If a creature's saving throw is successful, they're immune to the vorvolaka's Fear Aura for the next 24 hours. This ability does not function if the vorvolaka is unconscious.

**Magic Resistance.** The vorvolaka has advantage on saving throws against spells and other magical effects.

**Regeneration.** The vorvolaka regains 15 hit points at the start of its turn if it has at least 1 hit point. If the vorvolaka takes radiant damage, this trait doesn't function at the start of the vorvolaka's next turn.


---

### Actions

**Multiattack.** The vorvolaka makes two Talon attacks. It can replace one of the attacks with Rend Armor (if available).

**Talon.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 22 (4d8 + 4) piercing damage plus 14 (4d6) necrotic damage.

**Rend Armor (Recharge 4–6).** The vorvolaka makes a Talon attack against a creature. On a hit, the creature's AC is reduced by 2 for 1 minute. Creatures not wearing armor are immune to this effect, and the total reduction can't bring a creature below an AC of 10.


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