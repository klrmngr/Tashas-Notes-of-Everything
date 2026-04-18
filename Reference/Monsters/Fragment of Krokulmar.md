---
type: pc
race: "Aberration"
class:
 - "Fragment of Krokulmar"
subClass:
 - "CR 0"
cover: "Fragment of Krokulmar.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/0
  - source/kftgv
---
###### Fragment of Krokulmar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Fragment of Krokulmar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 16 | 12 | 16 | 16 | 16 |
| **Mod** | -3 | +3 | +1 | +3 | +3 | +3 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Deep Speech, telepathy 60 ft.
**Skills:** Arcana +7, History +7, Persuasion +7, Stealth +7
**Damage Immunities:** psychic

---

### Actions

**Psionic Revitalization.** The fragment touches one creature that has 0 hit points in the fragment's space. The target regains 10 hit points, and each creature within 10 feet of the healed creature takes 3 (1d6) psychic damage.

**Squirming Dodge.** Until the start of the fragment's next turn, any attack roll made against the fragment has disadvantage, and the fragment makes saving throws with advantage.


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