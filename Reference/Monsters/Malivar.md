---
type: pc
race: "Humanoid (human)"
class:
 - "Malivar"
subClass:
 - "CR 6"
cover: "Malivar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/aitfr-isf
---
###### Malivar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-ISF
___

> [!infobox|no-t right]
> ![[Malivar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | AitFR-ISF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 17 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Ignan, Infernal
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6

---

### Traits

**Benign Transportation (Recharges after Malivar Casts a Conjuration Spell of 1st Level or Higher).** As a bonus action, Malivar teleports up to 30 feet to an unoccupied space that he can see.
If he instead chooses a space within range that is occupied by a willing Small or Medium creature, they both teleport, swapping places.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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