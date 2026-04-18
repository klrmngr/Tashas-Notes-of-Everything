---
type: pc
race: "Humanoid (gith, wizard)"
class:
 - "Githyanki Gish"
subClass:
 - "CR 10"
cover: "Githyanki Gish.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mpmm
---
###### Githyanki Gish
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Githyanki Gish.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Humanoid (gith, wizard) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 14 | 16 | 15 | 16 |
| **Mod** | +3 | +2 | +2 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Gith
**Saving Throws:** Con +6, Int +7, Wis +6
**Skills:** Insight +6, Perception +6, Stealth +6

---

### Actions

**Multiattack.** The githyanki makes three Longsword or Telekinetic Bolt attacks, or it makes one of those attacks and uses Spellcasting.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands, plus 22 (5d8) psychic damage.

**Telekinetic Bolt.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 28 (8d6) force damage.


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