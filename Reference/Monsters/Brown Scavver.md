---
type: pc
race: "Monstrosity"
class:
 - "Brown Scavver"
subClass:
 - "CR 4"
cover: "Brown Scavver.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/bam
---
###### Brown Scavver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Brown Scavver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 51 (6d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 17 | 1 | 10 | 1 |
| **Mod** | +4 | +2 | +3 | -5 | +0 | -5 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —

---

### Traits

**Unusual Nature.** The scavver doesn't require air.


---

### Actions

**Swallowing Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 13 Dexterity saving throw or be swallowed by the scavver. The scavver can have one creature swallowed at a time.
A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the scavver, and takes 13 (3d8) poison damage at the start of each of the scavver's turns from the poisonous gas in the scavver's gullet.
If the scavver takes 15 damage or more on a single turn from a creature inside it, the scavver must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls prone in a space within 10 feet of the scavver. If the scavver dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 10 feet of movement, exiting prone.


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