---
type: pc
race: "Elemental"
class:
 - "Smoke Mephit"
subClass:
 - "CR 1/4"
cover: "Smoke Mephit.png"
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
###### Smoke Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Smoke Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 12 | 10 | 10 | 11 |
| **Mod** | -2 | +2 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Primordial (Auran, Ignan)
**Skills:** Perception +2, Stealth +4
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The mephit explodes when it dies. con DC 11, each creature in a 5-foot Emanation originating from the mephit.  The target has the Poisoned condition until the end of its next turn.


---

### Actions

**Claw.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage.

**Cinder Breath (Recharge 6).** dex DC 11, one creature the mephit can see within 15 feet.  The target has the Blinded condition until the end of the mephit's next turn.


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