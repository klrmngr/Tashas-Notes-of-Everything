---
type: pc
race: "Fiend"
class:
 - "Displacer Fiend"
subClass:
 - "CR 9"
cover: "Displacer Fiend.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/9
  - source/coa
---
###### Displacer Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Displacer Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 19 | 14 | 8 | 13 | 10 |
| **Mod** | +3 | +4 | +2 | -1 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Str +7, Dex +8
**Skills:** Acrobatics +8, Athletics +7, Perception +5, Stealth +12
**Damage Resistances:** fire; poison
**Condition Immunities:** charmed; frightened

---

### Traits

**Avoidance.** If the displacer fiend is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Displacement.** The displacer fiend projects a magical illusion that makes it appear to be standing near its actual location, causing attack rolls against it to have disadvantage. If it is hit by an attack, this trait is disrupted until the end of its next turn. This trait is also disrupted while the displacer fiend is incapacitated or has a speed of 0.


---

### Actions

**Multiattack.** The displacer fiend makes three Tentacle attacks. It can replace one of the attacks with a Bite attack.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 18 (4d6 + 4) piercing damage plus 7 (2d6) necrotic damage.

**Bite.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 23 (3d12 + 4) piercing damage, and the target's Dexterity score is reduced by 2 (1d4). The target is killed if this reduces its Dexterity to 0. The reduction lasts until the target finishes a short or long rest.


---

### Bonus Actions

**Shadowhop.** While in dim light or darkness, the displacer fiend can teleport up to 60 feet, provided its destination is also in dim light or darkness.


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