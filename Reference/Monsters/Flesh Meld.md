---
type: pc
race: "Aberration"
class:
 - "Flesh Meld"
subClass:
 - "CR 7"
cover: "Flesh Meld.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/7
  - source/pabtso
---
###### Flesh Meld
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Flesh Meld.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 95 (10d12 + 30) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 17 | 7 | 13 | 5 |
| **Mod** | +5 | +2 | +3 | -2 | +1 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 11
**Languages:** understands all but can't speak
**Saving Throws:** Str +8, Dex +5
**Condition Immunities:** blinded; prone

---

### Traits

**Amorphous.** The flesh meld can move through a space as narrow as 1 inch without squeezing.

**Aura of Death.** At the start of each of the flesh meld's turns, each creature within 5 feet of it must succeed on a DC 15 Constitution saving throw or take 3 (1d6) necrotic damage and have the poisoned condition until the start of the flesh meld's next turn.

**Magic Resistance.** The flesh meld has advantage on saving throws against spells and other magical effects.

**Spider Climb.** The flesh meld can climb difficult surfaces, including ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The flesh meld makes two Bite attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 30 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage, and if the target is a Large or smaller creature, it has the grappled condition (escape DC 15) and is pulled up to 15 feet toward the flesh meld.


---

### Bonus Actions

**Consume Creature.** The flesh meld targets one Large or smaller creature within 5 feet of itself that it's grappling. The target must succeed on a DC 15 Dexterity saving throw or be swallowed by the flesh meld. The flesh meld can have one creature swallowed at a time.
A swallowed creature no longer has the grappled condition. While swallowed, it has the blinded and restrained conditions, has 3 against attacks and other effects outside the flesh meld, and takes 10 (3d6) necrotic damage at the start of each of the flesh meld's turns. If this damage reduces a swallowed creature to 0 hit points, the creature dies, and the flesh meld consumes its body.
If the flesh meld takes 30 damage or more on a single turn from the swallowed creature, the flesh meld must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls with the prone condition in a space within 5 feet of the flesh meld. If the flesh meld dies, the swallowed creature is no longer restrained by it and can escape from the corpse by using 10 feet of movement, exiting with the prone condition.


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