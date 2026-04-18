---
type: pc
race: "Elemental"
class:
 - "Steam Mephit"
subClass:
 - "CR 1/4"
cover: "Steam Mephit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-4
  - source/xmm
---
###### Steam Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Steam Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 11 | 10 | 11 | 10 | 12 |
| **Mod** | -3 | +0 | +0 | +0 | +0 | +1 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Aquan, Ignan)
**Skills:** Stealth +2
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Blurred Form.** Attack rolls against the mephit are made with Disadvantage unless the mephit has the Incapacitated condition.

**Death Burst.** The mephit explodes when it dies. dex DC 10, each creature in a 5-foot Emanation originating from the mephit.  5 (2d4) Fire damage.  Half damage.


---

### Actions

**Claw.** m +2, reach 5 ft. *Hit:* 2 (1d4) Slashing damage plus 2 (1d4) Fire damage.

**Steam Breath (Recharge 6).** con DC 10, each creature in a 15-foot Cone.  5 (2d4) Fire damage, and the target's Speed decreases by 10 feet until the end of the mephit's next turn.  Half damage only.  Being underwater doesn't grant Resistance to this Fire damage.


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