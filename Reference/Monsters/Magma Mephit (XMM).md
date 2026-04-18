---
type: pc
race: "Elemental"
class:
 - "Magma Mephit"
subClass:
 - "CR 1/2"
cover: "Magma Mephit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-2
  - source/xmm
---
###### Magma Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Magma Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 12 | 12 | 7 | 10 | 10 |
| **Mod** | -1 | +1 | +1 | -2 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Ignan, Terran)
**Skills:** Stealth +3
**Damage Vulnerabilities:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The mephit explodes when it dies. dex DC 11, each creature in a 5-foot Emanation originating from the mephit.  7 (2d6) Fire damage.  Half damage.


---

### Actions

**Claw.** m +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Slashing damage plus 3 (1d6) Fire damage.

**Fire Breath (Recharge 6).** dex DC 11, each creature in a 15-foot Cone.  7 (2d6) Fire damage.  Half damage.


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