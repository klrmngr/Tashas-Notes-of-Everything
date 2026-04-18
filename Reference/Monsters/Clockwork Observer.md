---
type: pc
race: "Construct"
class:
 - "Clockwork Observer"
subClass:
 - "CR 0"
cover: "Clockwork Observer.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/kftgv
---
###### Clockwork Observer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Clockwork Observer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 7 (2d4 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 16 | 13 | 3 | 15 | 1 |
| **Mod** | -5 | +3 | +1 | -4 | +2 | -5 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands the languages of its creator but can't speak
**Skills:** Perception +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Flyby.** The observer doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Telepathic Bond.** While the observer is within 1 mile of its creator, it can magically convey what it sees to its creator, and the two can communicate telepathically.

**Unusual Nature.** The observer doesn't need air, food, drink, or sleep.


---

### Actions

**Shriek.** The observer emits a mechanical shriek until the start of its next turn or until it drops to 0 hit points. This shriek can be heard within a range of 300 feet.


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