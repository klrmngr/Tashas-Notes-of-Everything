---
type: pc
race: "Monstrosity"
class:
 - "Merrow Haranguer"
subClass:
 - "CR 5"
cover: "Merrow Haranguer.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/lfl
---
###### Merrow Haranguer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Merrow Haranguer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 16 | 14 | 15 | 19 |
| **Mod** | +4 | +4 | +3 | +2 | +2 | +4 |

**Speed:** 5 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Primordial (Aquan)
**Saving Throws:** Dex +7, Cha +7
**Skills:** Performance +7, Persuasion +7

---

### Traits

**Amphibious.** The merrow can breathe air and water.


---

### Actions

**Multiattack.** The merrow makes three attacks, using Coral Scepter and Poisoned Longbow in any combination.

**Coral Scepter.** m +7, reach 5 ft. *Hit:* 14 (2d10 + 4) Bludgeoning damage.

**Poisoned Longbow.** r +7, range 150/600 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 7 (2d6) Poison damage.

**Invective.** wis DC 15, up to three creatures the merrow can see within 60 feet.  14 (4d6) Psychic damage, and the creature has Disadvantage on its next attack roll before the end of the merrow's next turn.  Half damage only.


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