---
type: pc
race: "Aberration"
class:
 - "Flumph"
subClass:
 - "CR 1/8"
cover: "Flumph.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1-8
  - source/xmm
---
###### Flumph
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Flumph.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 10 | 14 | 14 | 11 |
| **Mod** | -2 | +2 | +0 | +2 | +2 | +0 |

**Speed:** 5 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands Undercommon but can't speak; telepathy 60 ft.
**Skills:** Arcana +4, History +4, Religion +4
**Damage Vulnerabilities:** psychic

---

### Traits

**Advanced Telepathy.** The flumph perceives the content of any telepathic communication within 60 feet of it.

**Prone Deficiency.** If the flumph receives the Prone condition, roll a die. On an odd number, it has the Incapacitated condition. At the end of each of its turns, the flumph makes a DC 10 Dexterity saving throw, ending the Incapacitated condition on a success.

**Telepathic Shroud.** The flumph's thoughts can't be read by any means, and magic can't detect its location or observe it remotely.


---

### Actions

**Tentacle.** m +4, reach 5 feet. *Hit:* 4 (1d4 + 2) Acid damage.

**Stench Spray (1/Day).** dex DC 10, one creature the flumph can see within 15 feet.  The target is coated in a foul-smelling liquid, exudes a stench for 1d4 hours, and has the Poisoned condition while the stench lasts. Other creatures have the Poisoned condition while in a 5-foot Emanation originating from the coated target. The target can remove the stench on itself if it bathes during a Short or Long Rest.


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