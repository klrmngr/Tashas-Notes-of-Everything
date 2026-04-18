---
type: pc
race: "Fey"
class:
 - "Mite"
subClass:
 - "CR 1/4"
cover: "Mite.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1-4
  - source/mff
---
###### Mite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Mite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 14 | 11 | 10 | 8 | 13 |
| **Mod** | -2 | +2 | +0 | +0 | -1 | +1 |

**Speed:** 30 ft., burrow 10 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Sylvan, Undercommon
**Skills:** Deception +3, Stealth +6

---

### Traits

**Vexing Presence.** While within 30 feet of a mite that can see it, a non-fey creature has disadvantage on Dexterity checks and Dexterity saving throws.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Blood Boiling Hex (Recharge 6).** The mite places a hex on a creature it can see within 60 feet of it for 1 minute. If the mite is hidden, using this ability does not reveal its location. While the creature is affected by this hex, whenever it makes an attack roll, an ability check, or a saving throw, it must roll a d6 and subtract the number rolled from the d20 roll. On any turn in which it suffers the effect of the hex, the target can attack an ally as a reaction, ignoring the effect of the hex when it does so. It can then ignore the effect of the hex until the end of its turn.


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