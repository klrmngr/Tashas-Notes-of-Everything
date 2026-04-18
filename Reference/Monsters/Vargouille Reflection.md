---
type: pc
race: "Fiend"
class:
 - "Vargouille Reflection"
subClass:
 - "CR 1"
cover: "Vargouille Reflection.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1
  - source/mpp
---
###### Vargouille Reflection
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Vargouille Reflection.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Fiend |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d4 + 10) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 14 | 6 | 10 | 2 |
| **Mod** | -2 | +2 | +2 | -2 | +0 | -4 |

**Speed:** 5 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands Abyssal, Infernal, and any languages it knew before becoming a vargouille, but it can't speak
**Damage Resistances:** cold; fire; lightning; psychic
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The vargouille has advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 10 (3d6) psychic damage.

**Abyssal Curse.** The vargouille targets one Humanoid within 5 feet of itself that has the incapacitated condition. The target must succeed on a DC 12 Charisma saving throw or become cursed. The cursed target's Charisma decreases by 1 after each hour, as its head takes on fiendish aspects, and its Charisma can't increase. The curse doesn't advance while the target is in sunlight or the area of a daylight spell. When the cursed target's Charisma becomes 2, the target dies, and its head tears from its body and becomes a new vargouille reflection. Casting remove curse, greater restoration, or a similar spell on the target before the transformation is complete ends the curse and restores the target's Charisma.

**Horrific Reflection (Recharge 5–6).** The vargouille's head mimics that of a Humanoid the vargouille can see within 120 feet of itself. The target must succeed on a DC 12 Wisdom saving throw or take 10 (3d6) psychic damage and have the frightened condition for 1 hour or until the vargouille loses concentration (as if concentrating on a spell). If the target's saving throw is successful or if the effect ends on it, the target is immune to the Horrific Reflection of all vargouille reflections for 1 hour.


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