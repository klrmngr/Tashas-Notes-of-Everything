---
type: pc
race: "Monstrosity"
class:
 - "Hertilod"
subClass:
 - "CR 17"
cover: "Hertilod.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/17
  - source/veor
---
###### Hertilod
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Hertilod.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 241 (21d12 + 105) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 18 | 20 | 3 | 15 | 10 |
| **Mod** | +6 | +4 | +5 | -4 | +2 | +0 |

**Speed:** 50 ft., climb 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 18
**Languages:** —
**Saving Throws:** Str +12, Dex +10
**Skills:** Perception +8
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Legendary Resistances (3/Day).** If the hertilod fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The hertilod has advantage on saving throws against spells and other magical effects.

**Shock Susceptibility.** If the hertilod takes lightning damage, its speed is halved until the end of its next turn, and it must succeed on a DC 15 Constitution saving throw or immediately regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the hertilod and has the prone condition.

**Spider Climb.** The hertilod can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The hertilod makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage plus 13 (2d12) poison damage. If the target is a Large or smaller creature, it must succeed on a DC 20 Strength saving throw or be swallowed by the hertilod. A swallowed creature has the blinded and restrained conditions, and it has 3 against attacks and other effects outside the hertilod. At the start of each of the hertilod's turns, each swallowed creature takes 13 (2d12) poison damage from the poisonous secretion in the hertilod's gullet.
The hertilod's gullet can hold up to two creatures at a time. If the hertilod takes 40 damage or more on a single turn from a swallowed creature, the hertilod must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the hertilod and has the prone condition. If the hertilod dies, a swallowed creature is no longer restrained and can escape from the corpse by using 10 feet of movement, exiting with the prone condition.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) slashing damage.


---

### Legendary Actions

### 

**Sprint.** The hertilod moves up to its speed. This movement doesn't provoke opportunity attacks.

**Feed (Costs 2 Actions).** The hertilod drains life from the creatures in its gullet to bolster itself. Each creature in the hertilod's gullet takes 10 (3d6) necrotic damage, and the hertilod regains a number of hit points equal to the damage.


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