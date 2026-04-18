---
type: pc
race: "Undead"
class:
 - "Zombie Clot"
subClass:
 - "CR 6"
cover: "Zombie Clot.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/6
  - source/vrgr
---
###### Zombie Clot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Zombie Clot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 104 (11d12 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 16 | 3 | 8 | 10 |
| **Mod** | +5 | +0 | +3 | -4 | -1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Con +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned; stunned

---

### Traits

**Deathly Stench.** Any creature that starts its turn within 10 feet of the zombie must succeed on a DC 14 Constitution saving throw or take 9 (2d8) poison damage and be poisoned until the start of the creature's next turn.

**Undead Fortitude.** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

**Unusual Nature.** The zombie doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The zombie makes two Slam attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (3d8 + 5) bludgeoning damage.

**Flesh Entomb (Recharge 5–6).** The zombie flings a detached clump of corpses at a creature it can see within 30 feet of it. The target must succeed on a DC 16 Strength saving throw or take 16 (3d10) bludgeoning damage, and if the target is a Large or smaller creature, it becomes entombed in dead flesh.
A creature entombed in the dead flesh is restrained, has 3 against attacks and other effects outside the dead flesh, and takes 10 (3d6) necrotic damage at the start of each of its turns. The creature can be freed if the dead flesh is destroyed. The dead flesh is a Large object with AC 10, 25 hit points, and immunity to poison and psychic damage.


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