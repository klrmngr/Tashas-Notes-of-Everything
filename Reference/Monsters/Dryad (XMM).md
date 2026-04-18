---
type: pc
race: "Fey"
class:
 - "Dryad"
subClass:
 - "CR 1"
cover: "Dryad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1
  - source/xmm
---
###### Dryad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dryad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 11 | 14 | 15 | 18 |
| **Mod** | +0 | +1 | +0 | +2 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Elvish, Sylvan
**Skills:** Perception +4, Stealth +5

---

### Traits

**Magic Resistance.** The dryad has Advantage on saving throws against spells and other magical effects.

**Speak with Beasts and Plants.** The dryad can communicate with Beasts and Plants as if they shared a language.


---

### Actions

**Multiattack.** The dryad makes one Vine Lash or Thorn Burst attack, and it can use Spellcasting to cast Charm Monster.

**Vine Lash.** m +6, reach 10 ft. *Hit:* 8 (1d8 + 4) Slashing damage.

**Thorn Burst.** r +6, range 60 ft. *Hit:* 7 (1d6 + 4) Piercing damage.


---

### Bonus Actions

**Tree Stride.** If within 5 feet of a Large or bigger tree, the dryad teleports to an unoccupied space within 5 feet of a second Large or bigger tree that is within 60 feet of the previous tree.


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