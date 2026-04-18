---
type: pc
race: "Humanoid"
class:
 - "Harmonium Captain"
subClass:
 - "CR 8"
cover: "Harmonium Captain.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/mpp
---
###### Harmonium Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Harmonium Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 14 | 12 | 16 | 16 |
| **Mod** | +4 | +0 | +2 | +1 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus one more language
**Saving Throws:** Str +7, Wis +6
**Skills:** Perception +6
**Condition Immunities:** charmed; frightened

---

### Traits

**Aura of Command.** Allies within 30 feet of the captain are immune to the charmed and frightened conditions. This aura is suppressed while the captain has the incapacitated condition.


---

### Actions

**Multiattack.** The captain makes three Harmonium Blade attacks. The captain can also use Dictate if available.

**Harmonium Blade.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 10 (3d6) lightning damage.

**Dictate (Recharge 5–6).** The captain verbally commands up to three creatures it can see within 60 feet of itself. This magical command must be to undertake an action or to refrain from taking actions (for example, "Throw down your weapons").
A target must succeed on a DC 14 Wisdom saving throw or have the charmed condition for 1 minute, during which time it follows the captain's command. The effect ends early if the target takes damage or if it successfully completes the command. A target automatically succeeds on its saving throw if the command is directly harmful to itself, such as commanding it to walk into fire.
A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.


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