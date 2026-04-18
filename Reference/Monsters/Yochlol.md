---
type: pc
race: "Fiend (demon, shapechanger)"
class:
 - "Yochlol"
subClass:
 - "CR 10"
cover: "Yochlol.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/10
  - source/mm
---
###### Yochlol
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Yochlol.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Fiend (demon, shapechanger) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 18 | 13 | 15 | 15 |
| **Mod** | +2 | +2 | +4 | +1 | +2 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Elvish, Undercommon
**Saving Throws:** Dex +6, Int +5, Wis +6, Cha +6
**Skills:** Deception +10, Insight +6
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The yochlol can use its action to polymorph into a form that resembles a female drow or giant spider, or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Magic Resistance.** The yochlol has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The yochlol can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Walker.** The yochlol ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The yochlol makes two melee attacks.

**Slam (Bite in Spider Form).** Melee Weapon Attack: +6 to hit, reach 5 ft. (10 feet in demon form), one target. *Hit:* 5 (1d6 + 2) bludgeoning (piercing in spider form) damage plus 21 (6d6) poison damage.

**Mist Form.** The yochlol transforms into toxic mist or reverts to its true form. Any equipment it is wearing or carrying is also transformed. It reverts to its true form if it dies.
While in mist form, the yochlol is incapacitated and can't speak. It has a flying speed of 30 feet, can hover, and can pass through any space that isn't airtight. It has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to nonmagical damage.
While in mist form, the yochlol can enter a creature's space and stop there. Each time that creature starts its turn with the yochlol in its space, the creature must succeed on a DC 14 Constitution saving throw or be poisoned until the start of its next turn. While poisoned in this way, the target is incapacitated.


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