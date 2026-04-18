---
type: pc
race: "Monstrosity"
class:
 - "Medusa"
subClass:
 - "CR 6"
cover: "Medusa.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/6
  - source/xmm
---
###### Medusa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Medusa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 16 | 12 | 13 | 15 |
| **Mod** | +0 | +3 | +3 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 150 ft., passive Perception 14
**Languages:** Common plus one other language
**Saving Throws:** Wis +4
**Skills:** Deception +5, Perception +4, Stealth +6

---

### Actions

**Multiattack.** The medusa makes two Claw attacks and one Snake Hair attack, or it makes three Poison Ray attacks.

**Claw.** m +6, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage.

**Snake Hair.** m +6, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage plus 14 (4d6) Poison damage.

**Poison Ray.** r +5, range 150 ft. *Hit:* 11 (2d8 + 2) Poison damage.


---

### Bonus Actions

**Petrifying Gaze (Recharge 5–6).** con DC 13, each creature in a 30-foot Cone. If the medusa sees its reflection in the Cone, the medusa must make this save. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.


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