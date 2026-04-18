---
type: pc
race: "Monstrosity"
class:
 - "Skulk"
subClass:
 - "CR 1/2"
cover: "Skulk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/mpmm
---
###### Skulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Skulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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
**Condition Immunities:** blinded

---

### Traits

**Fallible Invisibility.** The skulk is invisible. This invisibility can be circumvented by three things:
- **Charnel Candles.** The skulk appears as a dim, translucent form in the light of a candle made of fat rendered from a corpse whose identity is unknown.
- **Children.** Humanoid children, aged 10 and under, can see through this invisibility.
- **Reflective Surfaces.** The skulk appears as a drab, smooth-skinned biped if its reflection can be seen in a mirror or on another surface.

**Trackless.** The skulk leaves no tracks to indicate where it has been or where it's headed.


---

### Actions

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage plus 3 (1d6) necrotic damage.


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