---
type: pc
race: "Undead"
class:
 - "Coldlight Walker"
subClass:
 - "CR 5"
cover: "Coldlight Walker.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/idrotf
---
###### Coldlight Walker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Coldlight Walker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 17 | 8 | 10 | 8 |
| **Mod** | +2 | +0 | +3 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +2, Wis +3
**Damage Immunities:** cold
**Condition Immunities:** blinded; charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Blinding Light.** The walker sheds bright light in a 20-foot radius and dim light for an additional 20 feet. As a bonus action, the walker can target one creature in its bright light that it can see and force it to succeed on a DC 14 Constitution saving throw or be blinded until the start of the walker's next turn.

**Icy Doom.** Any creature killed by the walker freezes for 9 days, during which time it can't be thawed, harmed by fire, animated, or raised from the dead.

**Unusual Nature.** The walker doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The walker makes two attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) bludgeoning damage plus 14 (4d6) cold damage.

**Cold Ray.** Ranged Spell Attack: +3 to hit, range 60 ft., one target. *Hit:* 25 (4d10 + 3) cold damage.


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