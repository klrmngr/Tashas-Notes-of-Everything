---
type: pc
race: "Fey"
class:
 - "Incarnation of Vibrance"
subClass:
 - "CR 10"
cover: "Incarnation of Vibrance.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/10
  - source/lfl
---
###### Incarnation of Vibrance
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Incarnation of Vibrance.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Fey |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 17 | 20 | 10 | 16 | 21 |
| **Mod** | +5 | +3 | +5 | +0 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Sylvan; telepathy 120 ft.
**Saving Throws:** Con +9, Cha +9
**Damage Resistances:** radiant
**Condition Immunities:** blinded; charmed; deafened; frightened

---

### Traits

**Magic Resistance.** The incarnation has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The incarnation makes two Vine attacks and uses Radiant Blast. It can replace one vine attack with a use of Spellcasting to cast Blindness/Deafness if available.

**Vine.** m +9, reach 20 ft. *Hit:* 18 (3d8 + 5) Bludgeoning damage. If the target is the incarnation's size or smaller, it has the Grappled condition (escape DC 15) from one of two vines.

**Radiant Blast.** con DC 17, each creature of the incarnation's choice in a 20-foot Emanation originating from the incarnation.  The creature takes 14 (2d8 + 5) Radiant damage.  Half damage.


---

### Bonus Actions

**Shape-Shift.** The incarnation changes its size to Medium, Large, or Huge.

**Teleport.** The incarnation teleports up to 60 feet to an unoccupied space it can see. The incarnation can't teleport while it has a creature Grappled.


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