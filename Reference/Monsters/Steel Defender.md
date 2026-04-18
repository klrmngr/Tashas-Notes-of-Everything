---
type: pc
race: "Construct"
class:
 - "Steel Defender"
subClass:
 - "CR —"
cover: "Steel Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/efa
---
###### Steel Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Steel Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 5 + five times your Artificer level (the defender has a number of Hit Dice [d8s] equal to your Artificer level) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 4 | 10 | 6 |
| **Mod** | +2 | +1 | +2 | -3 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** understands the languages you know
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Steel Bond.** Add your Proficiency Bonus to any ability check or saving throw the defender makes.


---

### Actions

**Force-Empowered Rend.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 2 plus your Intelligence modifier Force damage.

**Repair (3/Day).** The defender, or one Construct or object it can see within 5 feet of itself, regains a number of Hit Points equal to 2d8 plus your Intelligence modifier.


---

### Reactions

**Deflect Attack.**  A creature the defender can see within 5 feet of itself makes an attack roll against a creature other than the defender.  The triggering creature makes the attack roll with Disadvantage.


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