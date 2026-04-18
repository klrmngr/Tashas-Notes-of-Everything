---
type: pc
race: "Monstrosity"
class:
 - "Void Scavver"
subClass:
 - "CR 11"
cover: "Void Scavver.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/11
  - source/bam
---
###### Void Scavver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Void Scavver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 157 (15d12 + 60) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 19 | 4 | 13 | 5 |
| **Mod** | +6 | +3 | +4 | -3 | +1 | -3 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +11

---

### Traits

**Unusual Nature.** The scavver doesn't require air.


---

### Actions

**Swallowing Bite.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 45 (6d12 + 6) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 16 Dexterity saving throw or be swallowed by the scavver. The scavver can have one creature swallowed at a time.
A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the scavver, and takes 11 (2d10) acid damage at the start of each of the scavver's turns from the digestive juices in the scavver's gullet.
If the scavver takes 25 damage or more on a single turn from a creature inside it, the scavver must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls prone in a space within 10 feet of the scavver. If the scavver dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 10 feet of movement, exiting prone.


---

### Bonus Actions

**Ray of Fear (Recharge 4–6).** The scavver's eye emits an invisible, magical ray that targets one creature the scavver can see within 60 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or be frightened of the scavver until the start of the scavver's next turn.


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