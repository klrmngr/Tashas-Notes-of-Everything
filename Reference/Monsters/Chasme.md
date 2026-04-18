---
type: pc
race: "Fiend (demon)"
class:
 - "Chasme"
subClass:
 - "CR 6"
cover: "Chasme.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/6
  - source/mm
---
###### Chasme
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Chasme.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 84 (13d10 + 13) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 15 | 12 | 11 | 14 | 10 |
| **Mod** | +2 | +2 | +1 | +0 | +2 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 120 ft., passive Perception 15
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Dex +5, Wis +5
**Skills:** Perception +5
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Drone.** The chasme produces a horrid droning sound to which demons are immune. Any other creature that starts its turn with in 30 feet of the chasme must succeed on a DC 12 Constitution saving throw or fall unconscious for 10 minutes. A creature that can't hear the drone automatically succeeds on the save. The effect on the creature ends if it takes damage or if another creature takes an action to splash it with holy water. If a creature's saving throw is successful or the effect ends for it, it is immune to the drone for the next 24 hours.

**Magic Resistance.** The chasme has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The chasme can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Proboscis.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 16 (4d6 + 2) piercing damage plus 24 (7d6) necrotic damage, and the target's hit point maximum is reduced by an amount equal to the necrotic damage taken. If this effect reduces a creature's hit point maximum to 0, the creature dies. This reduction to a creature's hit point maximum lasts until the creature finishes a long rest or until it is affected by a spell like  greater restoration.


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