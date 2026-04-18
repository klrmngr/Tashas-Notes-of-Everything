---
type: pc
race: "Humanoid (tiefling)"
class:
 - "Vanifer"
subClass:
 - "CR 9"
cover: "Vanifer.png"
campaign:
locations:
tags:
  - race/tiefling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/pota
---
###### Vanifer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Vanifer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (tiefling) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 17 | 12 | 13 | 19 |
| **Mod** | +0 | +3 | +3 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Ignan, Infernal
**Skills:** Arcana +5, Deception +8, Performance +8
**Damage Immunities:** fire

---

### Traits

**Funeral Pyre.** When Vanifer drops to 0 hit points, her body is consumed in a flash of fire and smoke. Anything she was wearing or carrying is left behind among ashes.

**Legendary Resistance (2/Day).** If Vanifer fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Vanifer makes two attacks.

**Tinderstrike.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 7 (2d6) fire damage.


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