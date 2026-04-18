---
type: pc
race: "Construct"
class:
 - "Duergar Hammerer"
subClass:
 - "CR 2"
cover: "Duergar Hammerer.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/2
  - source/mtf
---
###### Duergar Hammerer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Duergar Hammerer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 7 | 12 | 5 | 5 | 5 |
| **Mod** | +3 | -2 | +1 | -3 | -3 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 7
**Languages:** understands Dwarvish but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Engine of Pain.** Once per turn, a creature that attacks the hammerer can target the duergar trapped in it. The attacker has disadvantage on the attack roll. On a hit, the attack deals an extra 5 (1d10) damage to the hammerer, and the hammerer can respond by using its Multiattack with its reaction.

**Siege Monster.** The hammerer deals double damage to objects and structures.


---

### Actions

**Multiattack.** The hammerer makes two attacks: one with its claw and one with its hammer.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.

**Hammer.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.


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