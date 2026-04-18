---
type: pc
race: "Fiend (demon)"
class:
 - "Demodragon"
subClass:
 - "CR 5"
cover: "Demodragon.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/5
  - source/wtthc
---
###### Demodragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Demodragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 102 (12d12 + 24) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 15 | 8 | 12 | 10 |
| **Mod** | +4 | +0 | +2 | -1 | +1 | +0 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 11
**Languages:** —
**Saving Throws:** Con +5, Wis +4
**Damage Resistances:** acid; cold; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Baleful Presence.** Sources of light in a 120-foot Emanation originating from the demodragon flicker wildly. Nonmagical sources of Bright Light in that area instead shed Dim Light.

**Regeneration.** The demodragon regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point


---

### Actions

**Multiattack.** The demodragon makes two Bite attacks.

**Bite.** m +7, reach 10 ft.  *Hit:* 11 (2d6 + 4) Piercing damage plus 4 (1d8) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 13, each creature in a 30-foot-long, 5-foot-wide Line.  22 (4d10) Acid damage.  Half damage.


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