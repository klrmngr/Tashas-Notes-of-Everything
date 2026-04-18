---
type: pc
race: "Celestial"
class:
 - "Saleeth the Couatl"
subClass:
 - "CR 4"
cover: "Saleeth the Couatl.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/4
  - source/awm
---
###### Saleeth the Couatl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Saleeth the Couatl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 97 |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 20 | 17 | 18 | 20 | 18 |
| **Mod** | +3 | +5 | +3 | +4 | +5 | +4 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Magic Weapons.** The couatl's weapon attacks are magical.

**Shielded Mind.** The couatl is immune to scrying and to any effect that would sense its emotions, read its thoughts, or detect its location.


---

### Actions

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 8 (1d6 + 5) piercing damage. Target must make a DC 13 Constitution save, or fall unconscious. Another creature can use an action to shake the target awake.

**Constrict.** Melee Weapon Attack: +6 to hit, reach 10 ft., one Medium or smaller creature. *Hit:* 10 (2d6 + 3) bludgeoning damage. Target is grappled (escape DC 15). The couatl can constrain only one target at a time.

**Change Shape.** The couatl magically polymorphs into Challenge Rating=[&0;&4], or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the couatl's choice).
In a new form, the couatl retains its game statistics and ability to speak, but its AC, movement modes, Strength, Dexterity, and other actions are replaced by those of the new form, and it gains any statistics and capabilities (except class features, legendary actions, and lair actions) that the new form has but that it lacks. If the new form has a bite attack, the couatl can use its bite in that form.


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