---
type: pc
race: "Monstrosity"
class:
 - "Banderhobb"
subClass:
 - "CR 5"
cover: "Banderhobb.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/mpmm
---
###### Banderhobb
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Banderhobb.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 84 (8d10 + 40) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 20 | 11 | 14 | 8 |
| **Mod** | +5 | +1 | +5 | +0 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** understands Common and the languages of its creator but can't speak
**Skills:** Athletics +8, Stealth +7
**Condition Immunities:** charmed; frightened

---

### Traits

**Resonant Connection.** If the banderhobb has even a tiny piece of a creature or an object in its possession, such as a lock of hair or a splinter of wood, it knows the most direct route to that creature or object if it is within 1 mile of the banderhobb.


---

### Actions

**Multiattack.** The banderhobb makes one Bite attack and one Tongue attack. It can replace one attack with a use of Shadow Step.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) piercing damage, and the target is grappled (escape DC 16) if it is a Large or smaller creature. Until this grapple ends, the target is restrained, and the banderhobb can't use its Bite attack or Tongue attack on another target.

**Tongue.** Melee Weapon Attack: +8 to hit, reach 15 ft., one creature. *Hit:* 10 (3d6) necrotic damage, and the target must make a DC 16 Strength saving throw. On a failed save, the target is pulled to a space within 5 feet of the banderhobb.

**Shadow Step.** The banderhobb teleports up to 30 feet to an unoccupied space of dim light or darkness that it can see.

**Swallow.** Melee Weapon Attack: +8 to hit, reach 5 ft., one Medium or smaller creature grappled by the banderhobb. *Hit:* 15 (3d6 + 5) piercing damage. The creature is also swallowed, and the grapple ends. The swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the banderhobb, and it takes 10 (3d6) necrotic damage at the start of each of the banderhobb's turns. A creature reduced to 0 hit points in this way stops taking the necrotic damage and becomes stable.
The banderhobb can have only one creature swallowed at a time. While the banderhobb isn't incapacitated, it can regurgitate the creature at any time (no action required) in a space within 5 feet of it. The creature exits prone. If the banderhobb dies, it likewise regurgitates a swallowed creature.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, the banderhobb takes the Hide action.


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