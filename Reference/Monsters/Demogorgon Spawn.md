---
type: pc
race: "Fiend (demon)"
class:
 - "Demogorgon Spawn"
subClass:
 - "CR 2"
cover: "Demogorgon Spawn.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/wtthc
---
###### Demogorgon Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Demogorgon Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 13 | 8 | 12 | 7 |
| **Mod** | +3 | +2 | +1 | -1 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** cold; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Baleful Presence.** Sources of light in a 60-foot Emanation originating from the spawn flicker wildly. Nonmagical sources of Bright Light in that area instead shed Dim Light.

**Regeneration.** The spawn regains 5 Hit Points at the start of each of its turns if it has at least 1 Hit Point.

**Running Leap.** With a 10-foot running start, the spawn can Long Jump up to 30 feet.


---

### Actions

**Multiattack.** The spawn makes two Claw attacks.

**Claw.** m +5, reach 10 ft. *Hit:* 6 (1d6 + 3) Slashing damage.

**Bite.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13). While Grappled, the target has the Blinded condition.


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