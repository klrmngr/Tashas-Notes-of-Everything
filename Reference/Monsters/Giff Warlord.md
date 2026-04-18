---
type: pc
race: "Humanoid"
class:
 - "Giff Warlord"
subClass:
 - "CR 10"
cover: "Giff Warlord.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/bam
---
###### Giff Warlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Giff Warlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 18 | 14 | 14 | 18 |
| **Mod** | +6 | +2 | +4 | +2 | +2 | +4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Saving Throws:** Str +10, Dex +6, Con +8, Wis +6
**Skills:** Athletics +10, Insight +6, Intimidation +12

---

### Traits

**Firearms Knowledge.** The giff's mastery of its weapons enables it to ignore the loading property of any firearm.

**Legendary Resistance (2/Day).** If the giff fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The giff makes two Morningstar attacks.

**Morningstar.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.

**Double-Barreled Musket.** Ranged Weapon Attack: +6 to hit, range 40/120 ft., one target. *Hit:* 28 (4d12 + 2) piercing damage.


---

### Legendary Actions

### 

**Move.** The giff moves up to its speed without provoking opportunity attacks.

**Rallying Cry.** The giff ends the frightened condition on itself and each creature of its choice that it can see within 30 feet of it.

**Weapon of Choice (2 Actions).** The giff makes two Morningstar attacks or one Double-Barreled Musket attack.


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