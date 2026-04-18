---
type: pc
race: "Elemental"
class:
 - "Dust Mephit"
subClass:
 - "CR 1/2"
cover: "Dust Mephit.png"
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
###### Dust Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dust Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 14 | 10 | 9 | 11 | 10 |
| **Mod** | -3 | +2 | +0 | -1 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Primordial (Auran, Terran)
**Skills:** Perception +2, Stealth +4
**Damage Vulnerabilities:** fire
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The mephit explodes when it dies. dex DC 10, each creature in a 5-foot Emanation originating from the mephit.  5 (2d4) Bludgeoning damage.  Half damage.


---

### Actions

**Claw.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage.

**Blinding Breath (Recharge 6).** dex DC 10, each creature in a 15-foot Cone.  The target has the Blinded condition until the end of the mephit's next turn.


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