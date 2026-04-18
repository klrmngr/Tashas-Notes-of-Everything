---
type: pc
race: "Creature"
class:
 - "Huge Gray Ooze"
subClass:
 - "CR 8"
cover: "Huge Gray Ooze.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/huge
  - cr/8
  - source/wdmm
---
###### Huge Gray Ooze
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Huge Gray Ooze.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Creature |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | 152 (16d12 + 48) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +4 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Actions

**Multiattack.** As an action, it can make two attacks with its pseudopods.

**Pseudopod.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 21 (6d6) acid damage, or 42 (12d6) acid damage while the ooze is enlarged. If the target is wearing nonmagical metal armor, its armor is partly corroded and takes a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the ooze magically increases in size. While enlarged, the ooze is Gargantuan, doubles its damage dice with its pseudopod attack, and makes Strength checks and Strength saving throws with advantage.

**Invisibility (Recharges after a Short or Long Rest).** The ooze magically turns invisible for up to 1 hour until it attacks, it uses its Enlarge, or its concentration is broken (as if concentrating on a spell).


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