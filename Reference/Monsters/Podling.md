---
type: pc
race: "Plant"
class:
 - "Podling"
subClass:
 - "CR 1/2"
cover: "Podling.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/vrgr
---
###### Podling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Podling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 11 | 14 | 10 | 10 | 10 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +0 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 10
**Languages:** Deep Speech, the languages the creature knew in life
**Condition Immunities:** charmed; frightened

---

### Traits

**Semblance of Life.** The podling is a physical copy of a creature digested by a bodytaker plant. The podling has the digested creature's memories and behaves like that creature, but with occasional lapses. An observer familiar with the digested creature can recognize the discrepancies with a successful DC 20 Wisdom (Insight) check, or automatically if the podling does something in direct contradiction to the digested creature's established beliefs or behavior. The podling melts into a slurry when it dies, when the bodytaker plant that created it dies, or when the bodytaker plant dismisses it (no action required).

**Unusual Nature.** The podling doesn't require sleep.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.


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