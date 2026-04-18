---
type: pc
race: "Undead"
class:
 - "Banshee"
subClass:
 - "CR 4"
cover: "Banshee.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/mm
---
###### Banshee
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Banshee.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 58 (13d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 14 | 10 | 12 | 11 | 17 |
| **Mod** | -5 | +2 | +0 | +1 | +0 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish
**Saving Throws:** Wis +2, Cha +5
**Damage Resistances:** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Detect Life.** The banshee can magically sense the presence of living creatures up to 5 miles away that aren't undead or constructs. She knows the general direction they're in but not their exact locations.

**Incorporeal Movement.** The banshee can move through other creatures and objects as if they were 3. She takes 5 (1d10) force damage if she ends her turn inside an object.


---

### Actions

**Corrupting Touch.** Melee Spell Attack: +4 to hit, reach 5 ft., one target. *Hit:* 12 (3d6 + 2) necrotic damage.

**Horrifying Visage.** Each non-undead creature within 60 feet of the banshee that can see her must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. A frightened target can repeat the saving throw at the end of each of its turns, with disadvantage if the banshee is within line of sight, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the banshee's Horrifying Visage for the next 24 hours.

**Wail (1/Day).** The banshee releases a mournful wail, provided that she isn't in sunlight. This wail has no effect on constructs and undead. All other creatures within 30 feet of her that can hear her must make a DC 13 Constitution saving throw. On a failure, a creature drops to 0 hit points. On a success, a creature takes 10 (3d6) psychic damage.


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