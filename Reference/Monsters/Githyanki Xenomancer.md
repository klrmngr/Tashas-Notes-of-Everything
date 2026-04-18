---
type: pc
race: "Humanoid (druid, gith)"
class:
 - "Githyanki Xenomancer"
subClass:
 - "CR 9"
cover: "Githyanki Xenomancer.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/bam
---
###### Githyanki Xenomancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Githyanki Xenomancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (druid, gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 157 (21d8 + 63) |
> | :FasUserGroup: Race | Humanoid (druid, gith) |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 17 | 15 | 18 | 13 |
| **Mod** | +2 | +4 | +3 | +2 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Gith plus any four languages
**Saving Throws:** Dex +8, Con +7, Wis +8
**Skills:** Animal Handling +8, Nature +6, Perception +8, Survival +8

---

### Actions

**Multiattack.** The githyanki makes three Staff attacks, three Telekinetic Bolt attacks, or a combination thereof.

**Staff.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage when used with two hands, plus 14 (4d6) psychic damage.

**Telekinetic Bolt.** Ranged Spell Attack: +8 to hit, range 60 ft., one target. *Hit:* 20 (3d10 + 4) force damage.


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