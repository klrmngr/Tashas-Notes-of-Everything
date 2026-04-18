---
type: pc
race: "Ooze"
class:
 - "Ochre Jelly"
subClass:
 - "CR 2"
cover: "Ochre Jelly.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/large
  - cr/2
  - source/xmm
---
###### Ochre Jelly
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ochre Jelly.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Ooze |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 6 | 14 | 2 | 6 | 1 |
| **Mod** | +2 | -2 | +2 | -4 | -2 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** acid
**Damage Immunities:** lightning; slashing
**Condition Immunities:** charmed; deafened; exhaustion; frightened; grappled; prone; restrained

---

### Traits

**Amorphous.** The jelly can move through a space as narrow as 1 inch without expending extra movement to do so.

**Spider Climb.** The jelly can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Pseudopod.** m +4, reach 5 ft. *Hit:* 12 (3d6 + 2) Acid damage.


---

### Reactions

**Split.**  While the jelly is Large or Medium and has 10+ Hit Points, it becomes Bloodied or is subjected to Lightning or Slashing damage.  The jelly splits into two new Ochre Jellies. Each new jelly is one size smaller than the original jelly and acts on its Initiative. The original jelly's Hit Points are divided evenly between the new jellies (round down).


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