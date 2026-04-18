---
type: pc
race: "Aberration"
class:
 - "Blue Slaad"
subClass:
 - "CR 7"
cover: "Blue Slaad.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/7
  - source/xmm
---
###### Blue Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Blue Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 133 (14d10 + 56) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 18 | 7 | 7 | 9 |
| **Mod** | +5 | +2 | +4 | -2 | -2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Slaad; telepathy 60 ft.
**Skills:** Perception +1
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Magic Resistance.** The slaad has Advantage on saving throws against spells and other magical effects.

**Regeneration.** The slaad regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.


---

### Actions

**Multiattack.** The slaad makes three Mutating Claw attacks.

**Mutating Claw.** m +8, reach 10 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 3 (1d6) Poison damage. If the target is a Humanoid not cursed by a slaad, it is subjected to the following effect. con DC 15.  The target is cursed. The cursed target can't regain Hit Points, and its Hit Point maximum decreases by 10 (3d6) after every 24 hours and doesn't return to normal after finishing a Long Rest. If the curse reduces the target's Hit Point maximum to 0, the curse ends, and instead of dying, the target instantly transforms into a Red Slaad or, if it can cast spells of level 3 or higher, a Green Slaad. Only a Wish spell can reverse this transformation.


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