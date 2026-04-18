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
  - source/vgm
---
###### Swarm of Rot Grubs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
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
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 7 | 10 | 1 | 2 | 1 |
| **Mod** | -4 | -2 | +0 | -5 | -4 | -5 |

**Speed:** 5 ft., climb 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 6
**Languages:** —
**Damage Resistances:** piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny maggot. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Bites.** Melee Weapon Attack: +0 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* The target is infested by 1d4 rot grubs. At the start of each of the target's turns, the target takes 1d6 piercing damage per rot grub infesting it. Applying fire to the bite wound before the end of the target's next turn deals 1 fire damage to the target and kills these rot grubs. After this time, these rot grubs are too far under the skin to be burned. If a target infested by rot grubs ends its turn with 0 hit points, it dies as the rot grubs burrow into its heart and kill it. Any effect that cures disease kills all rot grubs infesting the target.


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