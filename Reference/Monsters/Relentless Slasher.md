---
type: pc
race: "Fiend"
class:
 - "Relentless Slasher"
subClass:
 - "CR 8"
cover: "Relentless Slasher.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/8
  - source/vrgr
---
###### Relentless Slasher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Relentless Slasher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 14 | 14 | 15 | 16 |
| **Mod** | +1 | +4 | +2 | +2 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** understands all languages but can't speak
**Saving Throws:** Str +4, Dex +7, Con +5, Wis +5
**Skills:** Athletics +7, Perception +5, Survival +5
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (1/Day).** If the slasher fails a saving throw, it can choose to succeed instead.

**Shrouded Presence.** The slasher is immune to any effect that would sense its emotions or read its thoughts, and it can't be detected by abilities that sense Fiends.


---

### Actions

**Multiattack.** The slasher makes two Slasher's Knife attacks.

**Slasher's Knife.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/60 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage plus 21 (6d6) necrotic damage. If the target is a creature, it suffers a lingering wound that causes it to take 7 (2d6) necrotic damage at the start of each of its turns. Each time the slasher hits the wounded target with this attack, the damage dealt by the wound increases by 3 (1d6). The wound ends if the target regains hit points or if a creature uses an action to stanch the wound, which requires a successful DC 15 Wisdom (Medicine) check.


---

### Legendary Actions

### 

**Slice.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/60 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Vanishing Strike (Costs 3 Actions).** The slasher makes one Slasher's Knife attack. After the attack hits or misses, the slasher can teleport up to 30 feet to an unoccupied space it can see.


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