---
type: pc
race: "Fiend (demon)"
class:
 - "Manes Vaporspawn"
subClass:
 - "CR 1"
cover: "Manes Vaporspawn.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/1
  - source/xmm
---
###### Manes Vaporspawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Manes Vaporspawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 15 | 5 | 8 | 3 |
| **Mod** | +2 | +1 | +2 | -3 | -1 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 9
**Languages:** understands Abyssal but can't speak
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; poisoned; restrained

---

### Traits

**Contortionist.** The manes can move through a space as narrow as 1 inch without expending extra movement to do so.

**Sickening Vapors.** con DC 12, each creature in a 5-foot Emanation originating from the manes at the end of the manes's turn.  The target has the Incapacitated condition until the end of its next turn.  The target is immune to this manes's Sickening Vapors for 24 hours.


---

### Actions

**Claw.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Slashing damage plus 5 (2d4) Necrotic damage.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the manes takes the Hide action.


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