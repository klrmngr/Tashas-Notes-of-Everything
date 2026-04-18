---
type: pc
race: "Construct"
class:
 - "Modron Pentadrone"
subClass:
 - "CR 2"
cover: "Modron Pentadrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/xmm
---
###### Modron Pentadrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Modron Pentadrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 32 (5d10 + 5) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 12 | 10 | 10 | 13 |
| **Mod** | +2 | +2 | +1 | +0 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 14
**Languages:** Modron
**Skills:** Perception +4
**Condition Immunities:** charmed

---

### Traits

**Disintegration.** If the modron dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.


---

### Actions

**Multiattack.** The modron makes five Slam attacks or five Electrical Discharge attacks.

**Slam.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Force damage.

**Electrical Discharge.** r +4, range 120 ft. *Hit:* 5 (1d6 + 2) Lightning damage.

**Paralysis Gas (Recharge 5–6).** Constitution Saving Throws: DC 11, each creature in a 30-foot Cone.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


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