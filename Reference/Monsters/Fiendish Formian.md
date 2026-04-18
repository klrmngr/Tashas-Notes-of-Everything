---
type: pc
race: "Fiend"
class:
 - "Fiendish Formian"
subClass:
 - "CR 4"
cover: "Fiendish Formian.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/coa
---
###### Fiendish Formian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Fiendish Formian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 10 | 12 | 11 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Formian
**Saving Throws:** Str +6
**Skills:** Acrobatics +4, Stealth +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Hive Mind.** All fiendish formians within 1 mile of Ekengarik can telepathically communicate with each other and Ekengarik.


---

### Actions

**Multiattack.** The fiendish formian makes two Claw attacks.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage and the target must make a DC 14 Constitution saving throw. On a failed save, the target's Strength score is reduced by 1. The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.


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