---
type: pc
race: "Construct"
class:
 - "Broom of Animated Attack"
subClass:
 - "CR 1/4"
cover: "Broom of Animated Attack.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/cos
---
###### Broom of Animated Attack
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Broom of Animated Attack.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 10 | 1 | 5 | 1 |
| **Mod** | +0 | +3 | +0 | -5 | -3 | -5 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 7
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Constructed Nature.** An animated object doesn't require air, food, drink, or sleep.
The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

**Antimagic Susceptibility.** The broom is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the broom must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**False Appearance.** While the broom remains motionless and isn't flying, it is indistinguishable from a normal broom.


---

### Actions

**Multiattack.** The broom makes two melee attacks.

**Broomstick.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.


---

### Reactions

**Animated Attack.** If the broom is motionless and a creature grabs hold of it, the broom makes a Dexterity check contested by the creature's Strength check. If the broom wins the contest, it flies out of the creature's grasp and makes a melee attack against it with advantage on the attack roll.


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