---
type: pc
race: "Humanoid (gith, warlock)"
class:
 - "Githyanki Star Seer"
subClass:
 - "CR 7"
cover: "Githyanki Star Seer.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/bam
---
###### Githyanki Star Seer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Githyanki Star Seer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (mage armor) |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid (gith, warlock) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 11 | 14 | 19 | 16 | 14 |
| **Mod** | +0 | +0 | +2 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Gith
**Saving Throws:** Con +5, Int +7, Wis +6
**Skills:** Arcana +10, History +10
**Damage Resistances:** radiant

---

### Actions

**Multiattack.** The githyanki makes three Astral Bolt attacks.

**Astral Bolt.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 20 (3d10 + 4) radiant damage.


---

### Bonus Actions

**Astral Step (Recharge 4–6).** The githyanki teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


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