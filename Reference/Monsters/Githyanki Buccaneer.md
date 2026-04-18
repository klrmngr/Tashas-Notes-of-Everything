---
type: pc
race: "Humanoid (gith)"
class:
 - "Githyanki Buccaneer"
subClass:
 - "CR 3"
cover: "Githyanki Buccaneer.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bam
---
###### Githyanki Buccaneer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Githyanki Buccaneer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 16 | 13 | 13 |
| **Mod** | +3 | +2 | +2 | +3 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Gith
**Saving Throws:** Con +4, Int +5, Wis +3
**Skills:** Athletics +5, Deception +3, Perception +3, Survival +3

---

### Actions

**Multiattack.** The githyanki makes two Greatsword or Telekinetic Bolt attacks.

**Greatsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage plus 3 (1d6) psychic damage.

**Telekinetic Bolt.** Ranged Spell Attack: +5 to hit, range 60 ft., one target. *Hit:* 13 (3d6 + 3) force damage.


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