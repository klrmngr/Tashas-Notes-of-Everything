---
type: pc
race: "Aberration (beholder)"
class:
 - "Spectator"
subClass:
 - "CR 3"
cover: "Spectator.png"
campaign:
locations:
tags:
  - race/beholder
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/xmm
---
###### Spectator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spectator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration (beholder) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Aberration (beholder) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 14 | 13 | 14 | 11 |
| **Mod** | -1 | +2 | +2 | +1 | +2 | +0 |

**Speed:** 5 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, Undercommon; telepathy 120 ft.
**Skills:** Perception +6
**Condition Immunities:** exhaustion; prone

---

### Actions

**Multiattack.** The spectator uses Eye Rays twice.

**Bite.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.

**Eye Rays.** The spectator randomly shoots one of the following magical rays at a target it can see within 90 feet of itself (roll 1d4; reroll if the spectator has already used that ray during this turn):
- **1: Confusion Ray.** wis DC 12.  5 (2d4) Psychic damage, and the target can't take Reactions until the end of its next turn. On its next turn, the target can't move, and it uses its action to make a melee or ranged attack against a randomly determined creature within range. If the target can't attack, it does nothing on that turn.
- **2: Paralyzing Ray.** con DC 12.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- **3: Fear Ray.** wis DC 12.  5 (2d4) Psychic damage, and the target has the Frightened condition until the end of its next turn.
- **4: Wounding Ray.** con DC 12.  16 (3d10) Necrotic damage.  Half damage.


---

### Reactions

**Spell Reflection.**  The spectator succeeds on a saving throw against a spell, or a spell's attack roll misses it. ddex DC 12, one creature the spectator can see within 120 feet.  10 (3d6) Force damage.


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