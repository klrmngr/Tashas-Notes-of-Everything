---
type: pc
race: "Fiend"
class:
 - "Rakshasa"
subClass:
 - "CR 13"
cover: "Rakshasa.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/mm
---
###### Rakshasa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Rakshasa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 110 (13d8 + 52) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 18 | 13 | 16 | 20 |
| **Mod** | +2 | +3 | +4 | +1 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Infernal
**Skills:** Deception +10, Insight +8
**Damage Vulnerabilities:** piercing from magic weapons wielded by good creatures
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Limited Magic Immunity.** The rakshasa can't be affected or detected by spells of 6th level or lower unless it wishes to be. It has advantage on saving throws against all other spells and magical effects.


---

### Actions

**Multiattack.** The rakshasa makes two claw attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage, and the target is cursed if it is a creature. The magical curse takes effect whenever the target takes a short or long rest, filling the target's thoughts with horrible images and dreams. The cursed target gains no benefit from finishing a short or long rest. The curse lasts until it is lifted by a remove curse spell or similar magic.


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