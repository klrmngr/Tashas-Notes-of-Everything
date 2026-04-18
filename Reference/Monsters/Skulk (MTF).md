---
type: pc
race: "Humanoid"
class:
 - "Skulk"
subClass:
 - "CR 1/2"
cover: "Skulk.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/mtf
---
###### Skulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Skulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 19 | 10 | 10 | 7 | 1 |
| **Mod** | -2 | +4 | +0 | +0 | -2 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 8
**Languages:** understands Common but can't speak
**Saving Throws:** Con +2
**Skills:** Stealth +8
**Damage Immunities:** radiant
**Condition Immunities:** blinded

---

### Traits

**Fallible Invisibility.** The skulk is invisible. This invisibility can be circumvented by three things:
- The skulk appears as a drab, smooth-skinned humanoid if its reflection can be seen in a mirror or on another surface.
- The skulk appears as a dim, translucent form in the light of a candle made of fat rendered from a corpse whose identity is unknown.
- Humanoid children, aged 10 and under, can see through this invisibility.

**Trackless.** The skulk leaves no tracks to indicate where it has been or where it's headed.


---

### Actions

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage. If the skulk has advantage on the attack roll, the target also takes 7 (2d6) necrotic damage.


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