---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Rot Grubs"
subClass:
 - "CR 1/2"
cover: "Swarm of Rot Grubs.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-2
  - source/mpmm
---
###### Swarm of Rot Grubs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Swarm of Rot Grubs.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 7 | 10 | 1 | 2 | 1 |
| **Mod** | -4 | -2 | +0 | -5 | -4 | -5 |

**Speed:** 5 ft., climb 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 6
**Languages:** —
**Damage Vulnerabilities:** fire
**Damage Resistances:** piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny maggot. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Bites.** Melee Weapon Attack: +0 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 7 (2d6) piercing damage, and the target must succeed on a DC 10 Constitution saving throw or be poisoned. At the end of each of the poisoned target's turns, the target takes 3 (1d6) poison damage. Whenever the poisoned target takes fire damage, the target can repeat the saving throw, ending the effect on itself on a success. If the poisoned target ends its turn with 0 hit points, it dies.


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