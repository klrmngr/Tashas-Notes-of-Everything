---
type: pc
race: "Monstrosity"
class:
 - "Wurm"
subClass:
 - "CR 14"
cover: "Wurm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/14
  - source/ggr
---
###### Wurm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Wurm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 10 | 22 | 3 | 12 | 4 |
| **Mod** | +7 | +0 | +6 | -4 | +1 | -3 |

**Speed:** 50 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., tremorsense 60 ft., passive Perception 11
**Languages:** —
**Saving Throws:** Con +11, Wis +6

---

### Traits

**Siege Monster.** The wurm deals double damage to objects and structures.

**Earth Tremors.** The wurm creates earth tremors as it moves overland or underground. Any creature that comes within 30 feet of the moving wurm for the first time on a turn must succeed on a DC 20 Dexterity saving throw or take 10 (3d6) bludgeoning damage and fall prone. Any structure or object anchored to the ground that comes within 30 feet of the moving wurm for the first time on a turn takes 10 (3d6) force damage.

**Tunneler.** The wurm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 24 (5d6 + 7) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 20 Dexterity saving throw or be swallowed by the wurm. A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the wurm, and takes 17 (5d6) acid damage at the start of each of the wurm's turns. If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.


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