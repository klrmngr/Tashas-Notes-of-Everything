---
type: pc
race: "Humanoid"
class:
 - "Zhentilar Paladin of Bane"
subClass:
 - "CR 4"
cover: "Zhentilar Paladin of Bane.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/fraif
---
###### Zhentilar Paladin of Bane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Zhentilar Paladin of Bane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 12 | 13 | 17 |
| **Mod** | +3 | +0 | +2 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common
**Saving Throws:** Str +5, Cha +5
**Skills:** Athletics +5, Intimidation +5, Religion +3

---

### Traits

**Aura of Dread.** Creatures in a 10-foot Emanation originating from the Zhentilar have their Speeds halved while in the Emanation. The Zhentilar can designate creatures to be unaffected by the aura.


---

### Actions

**Multiattack.** The Zhentilar makes three attacks, using Dooming Blade or Oppressive Ray in any combination. It can replace one attack with a use of Spellcasting.

**Dooming Blade.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage plus 7 (2d6) Necrotic damage.

**Oppressive Ray.** r +5, range 90 ft. *Hit:* 16 (3d10) Psychic damage.


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