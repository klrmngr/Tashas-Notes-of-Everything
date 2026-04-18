---
type: pc
race: "Construct"
class:
 - "Alyxian the Hunter"
subClass:
 - "CR 10"
cover: "Alyxian the Hunter.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/10
  - source/crcotn
---
###### Alyxian the Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Alyxian the Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 9 | 20 | 3 | 11 | 1 |
| **Mod** | +6 | -1 | +5 | -4 | +0 | -5 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The golem is immune to any spell or effect that would alter its form.

**Magic Resistance.** The golem has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The golem's weapon attacks are magical.


---

### Actions

**Multiattack.** The golem makes two slam attacks.

**Ruidium Dart.** The golem can conjure a magic dart made of ruidium and hurl it at another creature it can see within 120 feet of itself. The dart strikes the target unerringly and vanishes on contact. The target must make a DC 17 Charisma saving throw. On a failed saving throw, the target takes 24 (7d6) psychic damage and gains 1 level of exhaustion. In addition, if the target is not already suffering from ruidium corruption, it becomes corrupted when it fails the saving throw. On a successful saving throw, the target takes half as much damage and suffers no other effects.

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage.

**Slow (Recharge 5–6).** The golem targets one or more creatures it can see within 10 feet of it. Each target must make a DC 17 Wisdom saving throw against this magic. On a failed save, a target can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the target can take either an action or a bonus action on its turn, not both. These effects last for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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