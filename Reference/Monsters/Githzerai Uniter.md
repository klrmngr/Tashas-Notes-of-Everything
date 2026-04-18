---
type: pc
race: "Aberration (gith)"
class:
 - "Githzerai Uniter"
subClass:
 - "CR 7"
cover: "Githzerai Uniter.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/7
  - source/mpp
---
###### Githzerai Uniter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Githzerai Uniter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (psychic defense) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 17 | 15 | 15 | 17 | 16 |
| **Mod** | +1 | +3 | +2 | +2 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Gith
**Saving Throws:** Str +4, Dex +6, Int +5, Wis +6
**Skills:** Insight +6, Perception +6

---

### Traits

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes three Unarmed Strike or Psychic Bolt attacks. It can replace any of these attacks with one use of its Pacifying Touch.

**Unarmed Strike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage plus 10 (3d6) psychic damage.

**Psychic Bolt.** Ranged Spell Attack: +6 to hit, range 60 ft., one creature. *Hit:* 17 (5d6) psychic damage.

**Pacifying Touch.** The githzerai touches one creature it can see within 5 feet of itself. The target must succeed on a DC 14 Intelligence saving throw, or the githzerai chooses an action for that target: Attack, Cast a Spell, or Dash. The affected target can't take that action for 1 minute. At the end of each of the target's turns, it can repeat the saving throw, ending the effect on itself on a successful save. A target that succeeds on the saving throw becomes immune to this githzerai's Pacifying Touch for 24 hours.


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