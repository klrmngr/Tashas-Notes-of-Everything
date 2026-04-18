---
type: pc
race: "Monstrosity"
class:
 - "Merrow"
subClass:
 - "CR 2"
cover: "Merrow.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/2
  - source/xmm
---
###### Merrow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Merrow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 15 | 8 | 10 | 9 |
| **Mod** | +4 | +2 | +2 | -1 | +0 | -1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Primordial (Aquan)

---

### Traits

**Amphibious.** The merrow can breathe air and water.


---

### Actions

**Multiattack.** The merrow makes two attacks, using Bite, Claw, or Harpoon in any combination.

**Bite.** m +6, reach 5 ft. *Hit:* 6 (1d4 + 4) Piercing damage, and the target has the Poisoned condition until the end of the merrow's next turn.

**Claw.** m +6, reach 5 ft. *Hit:* 9 (2d4 + 4) Slashing damage.

**Harpoon.** m,r +6, reach 5 ft. or range 20/60 ft. *Hit:* 11 (2d6 + 4) Piercing damage. If the target is a Large or smaller creature, the merrow pulls the target up to 15 feet straight toward itself.


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