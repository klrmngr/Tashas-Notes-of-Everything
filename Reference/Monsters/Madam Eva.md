---
type: pc
race: "Humanoid (human)"
class:
 - "Madam Eva"
subClass:
 - "CR 10"
cover: "Madam Eva.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/cos
---
###### Madam Eva
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Madam Eva.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 11 | 12 | 17 | 20 | 18 |
| **Mod** | -1 | +0 | +1 | +3 | +5 | +4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 19
**Languages:** Abyssal, Common, Elvish, Infernal
**Saving Throws:** Con +5
**Skills:** Arcana +7, Deception +8, Insight +13, Intimidation +8, Perception +9, Religion +7

---

### Actions

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) piercing damage.

**Curse (Recharges after a Long Rest).** Madam Eva targets one creature that she can see within 30 feet of her. The target must succeed on a DC 17 Wisdom saving throw or be cursed. While cursed, the target is blinded and deafened. The curse lasts until ended with a greater restoration spell, a remove curse spell, or similar magic. When the curse ends, Madam Eva takes 5d6 psychic damage.

**Evil Eye (Recharges after a Short or Long Rest).** Madam Eva targets one creature that she can see within 10 feet of her and casts one of the following spells on the target (save DC 17), requiring neither somatic nor material components to do so: animal friendship, charm person, or hold person. If the target succeeds on the initial saving throw, Madam Eva is blinded until the end of her next turn. Once a target succeeds on a saving throw against this effect, it is immune to the Evil Eye power of all Vistani for 24 hours.


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