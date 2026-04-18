---
type: pc
race: "Aberration"
class:
 - "Corrupted Giant Shark"
subClass:
 - "CR 9"
cover: "Corrupted Giant Shark.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/9
  - source/crcotn
---
###### Corrupted Giant Shark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Corrupted Giant Shark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 21 | 1 | 10 | 5 |
| **Mod** | +6 | +0 | +5 | -5 | +0 | -3 |

**Speed:** 0 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Traits

**Psychic Maelstrom.** Any creature that starts its turn within 15 feet of the shark must succeed on a DC 17 Wisdom saving throw or take 11 (2d10) psychic damage.

**Regeneration.** The shark regains 10 hit points at the start of its turn. If the shark takes radiant damage or suffers a critical hit, this trait doesn't function at the start of its next turn. The shark dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Water Breathing.** The shark can breathe only underwater.


---

### Actions

**Bite.** Melee Weapon Attack: +10 to hit (with advantage if the target is a creature missing any hit points), reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage, and if the target is a creature, it must succeed on a DC 17 Charisma saving throw or gain 1 level of exhaustion.


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