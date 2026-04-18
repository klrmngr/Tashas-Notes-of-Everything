---
type: pc
race: "Humanoid"
class:
 - "Bullywug Knight"
subClass:
 - "CR 3"
cover: "Bullywug Knight.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wbtw
---
###### Bullywug Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Bullywug Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 13 | 9 | 11 | 14 |
| **Mod** | +3 | +1 | +1 | -1 | +0 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Bullywug, Common
**Saving Throws:** Con +3, Wis +2

---

### Traits

**Amphibious.** The knight can breathe air and water.

**Speak with Frogs and Toads.** The knight can communicate simple concepts to frogs and toads when it speaks in Bullywug.

**Standing Leap.** The knight's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Multiattack.** The knight makes two Glaive attacks.

**Glaive.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 8 (1d10 + 3) slashing damage.


---

### Bonus Actions

**Croak of Charming (Recharges after a Short or Long Rest).** The knight makes a loud croak while targeting one creature it can see within 30 feet of it. The target must succeed on a DC 12 Wisdom saving throw or be charmed until the end of its next turn.


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