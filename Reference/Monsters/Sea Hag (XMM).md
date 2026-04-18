---
type: pc
race: "Fey"
class:
 - "Sea Hag"
subClass:
 - "CR 2"
cover: "Sea Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/xmm
---
###### Sea Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sea Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 16 | 12 | 12 | 13 |
| **Mod** | +3 | +1 | +3 | +1 | +1 | +1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common, Giant, Primordial (Aquan)

---

### Traits

**Amphibious.** The hag can breathe air and water.

**Vile Appearance.** wis DC 11, any Beast or Humanoid that starts its turn within 30 feet of the hag and can see the hag's true form.  The target has the Frightened condition until the start of its next turn.  The target is immune to this hag's Vile Appearance for 24 hours.


---

### Actions

**Claw.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage.

**Death Glare (Recharge 5–6).** wis DC 11, one Frightened creature the hag can see within 30 feet.  If the target has 20 Hit Points or fewer, it drops to 0 Hit Points. Otherwise, the target takes 13 (3d8) Psychic damage.


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