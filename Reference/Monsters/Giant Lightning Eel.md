---
type: pc
race: "Beast"
class:
 - "Giant Lightning Eel"
subClass:
 - "CR 3"
cover: "Giant Lightning Eel.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/tftyp
---
###### Giant Lightning Eel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Giant Lightning Eel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 42 (5d10 + 15) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 16 | 2 | 12 | 3 |
| **Mod** | +0 | +3 | +3 | -4 | +1 | -4 |

**Speed:** 5 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 11
**Languages:** —
**Damage Resistances:** lightning

---

### Traits

**Water Breathing.** The eel can breathe only underwater.


---

### Actions

**Multiattack.** The eel makes two bite attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage plus 4 (1d8) lightning damage.

**Lightning Jolt (Recharge 5–6).** One creature the eel touches within 5 feet of it outside water, or each creature within 15 feet of it in a body of water, must make a DC 12 Constitution saving throw. On failed save, a target takes 13 (3d8) lightning damage. If the target takes any of this damage, the target is stunned until the end of the eel's next turn. On a successful save, a target takes half as much damage and isn't stunned.


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