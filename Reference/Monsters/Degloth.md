---
type: pc
race: "Fiend (demon)"
class:
 - "Degloth"
subClass:
 - "CR 11"
cover: "Degloth.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/veor
---
###### Degloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Degloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 133 (14d10 + 56) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 17 | 18 | 6 | 11 | 9 |
| **Mod** | +6 | +3 | +4 | -2 | +0 | -1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +10, Con +8
**Skills:** Athletics +10, Perception +4
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Magic Resistance.** The degloth has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The degloth makes two Razor Fist attacks.

**Razor Fist.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) slashing damage, and if the target is a Medium or smaller creature, the target has the grappled condition (escape DC 18). Until this grapple ends, the target has the restrained condition, and the degloth can't use this fist to grapple another target. The degloth has two fists.


---

### Bonus Actions

**Crush.** The degloth targets one creature currently grappled by it. The target must make a DC 18 Strength saving throw, taking 15 (2d8 + 6) bludgeoning damage on a failed save or half as much damage on a successful one.


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