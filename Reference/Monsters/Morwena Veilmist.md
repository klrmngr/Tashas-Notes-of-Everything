---
type: pc
race: "Humanoid (human)"
class:
 - "Morwena Veilmist"
subClass:
 - "CR 5"
cover: "Morwena Veilmist.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/aitfr-thp
---
###### Morwena Veilmist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-THP
___

> [!infobox|no-t right]
> ![[Morwena Veilmist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | AitFR-THP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 13 | 17 | 12 | 14 |
| **Mod** | -1 | +2 | +1 | +3 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any four languages
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6

---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d6-1) bludgeoning damage, or 3 (1d8-1) bludgeoning damage if used with two hands.


---

### Reactions

**Instinctive Charm (Recharges after Morwena Casts an Enchantment Spell of 1st Level or Higher).** Morwena tries to magically divert an attack made against her, provided that the attacker is within 30 feet of her and visible to her. She must decide to do so before the attack hits or misses.
The attacker must make a DC 15 Wisdom saving throw. On a failed save, the attacker targets the creature closest to it, other than Morwena or itself. If multiple creatures are closest, the attacker chooses which one to target.


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