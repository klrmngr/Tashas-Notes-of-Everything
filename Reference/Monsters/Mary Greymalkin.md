---
type: pc
race: "Humanoid"
class:
 - "Mary Greymalkin"
subClass:
 - "CR 2"
cover: "Mary Greymalkin.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/llk
---
###### Mary Greymalkin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Laboratory of Kwalish
___

> [!infobox|no-t right]
> ![[Mary Greymalkin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 (Bracers of Defense, Ring of Protection) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Lost Laboratory of Kwalish |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 14 | 14 | 15 |
| **Mod** | +0 | +1 | +0 | +2 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Celestial, Common, Elvish, Infernal, Sylvan
**Saving Throws:** Wis +4, Cha +4
**Skills:** Arcana +4, Medicine +4, Nature +4, Religion +4

---

### Traits

**Special Equipment.** Mary wears Bracers of Defense and a Ring of Protection, and carries a Deck of Several Things

**Fey Presence (Recharges after a Short Rest).** Mary can cause each creature within 10 feet of her to succeed on a DC 12 Wisdom saving throw or become charmed or frightened by her (Mary's choice) until the end of her next turn.

**Fey Ancestry.** Mary has advantage on saving throws against being charmed, and magic can't put her to sleep.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage.


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