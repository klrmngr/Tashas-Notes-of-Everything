---
type: pc
race: "Monstrosity"
class:
 - "Blazebear"
subClass:
 - "CR 12"
cover: "Blazebear.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/12
  - source/veor
---
###### Blazebear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Blazebear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 17 | 21 | 3 | 13 | 16 |
| **Mod** | +7 | +3 | +5 | -4 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Str +11, Cha +7
**Skills:** Perception +5

---

### Traits

**Magic Resistance.** The blazebear has advantage on saving throws against spells and other magical effects.

**Mist Sight.** The blazebear can see normally through heavily obscured areas created by mist or fog, including areas created by spells such as Fog Cloud.


---

### Actions

**Multiattack.** The blazebear makes two Bite attacks. It can replace one attack with Stunning Gaze if available.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 20 (2d12 + 7) piercing damage plus 11 (2d10) force damage.

**Stunning Gaze (Recharge 5–6).** The blazebear targets two creatures it can see within 120 feet of itself. Each target must succeed on a DC 15 Wisdom saving throw or have the stunned condition until the start of the blazebear's next turn.


---

### Reactions

**Antimagic Swipe.** Melee Weapon Attack: +11 to hit, reach 10 ft., one creature casting a spell of 3rd level or lower. *Hit:* 22 (4d10) force damage, and the target must succeed on a DC 15 Intelligence saving throw or the spell fails and has no effect.


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