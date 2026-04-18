---
type: pc
race: "Fey"
class:
 - "Incarnation of Transience"
subClass:
 - "CR 7"
cover: "Incarnation of Transience.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/7
  - source/lfl
---
###### Incarnation of Transience
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Incarnation of Transience.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Fey |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 142 (15d12 + 45) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 20 | 17 | 10 | 14 | 16 |
| **Mod** | +5 | +5 | +3 | +0 | +2 | +3 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Sylvan; telepathy 120 ft.
**Saving Throws:** Dex +8, Con +6
**Condition Immunities:** grappled; paralyzed; petrified; prone; restrained

---

### Traits

**Ephemeral Movement.** The incarnation can move through other creatures and objects as if they were Difficult Terrain, and its movement doesn't provoke Opportunity Attacks. It takes 5 (1d10) Force damage if it ends its turn inside an object.

**Magic Resistance.** The incarnation has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The incarnation makes three attacks, using Bite or Miasmic Globule in any combination.

**Bite.** m +8, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing damage.

**Miasmic Globule.** r +8, range 60/120 ft. *Hit:* 15 (6d4) Acid damage, and the target's Speed is reduced by 10 feet until the end of the incarnation's next turn.

**Spectral Stampede.** The incarnation moves up to 80 feet in a straight line. Each creature whose space the incarnation enters is targeted once by the following effect. dex DC 16.  18 (4d8) Force damage. If the target is the incarnation's size or smaller, it has the Prone condition.  Half damage only.


---

### Bonus Actions

**Shape-Shift.** The incarnation changes its size to Medium, Large, or Huge.


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