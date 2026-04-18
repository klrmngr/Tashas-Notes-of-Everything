---
type: pc
race: "Humanoid (human)"
class:
 - "Mr. Greystone"
subClass:
 - "CR 5"
cover: "Mr. Greystone.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/nrh-at
---
###### Mr. Greystone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NRH-AT
___

> [!infobox|no-t right]
> ![[Mr. Greystone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | NRH-AT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 10 | 12 | 15 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Goblin
**Saving Throws:** Str +7, Dex +5, Con +6
**Skills:** Athletics +10, Intimidation +5

---

### Traits

**Brave.** Mr. Greystone has advantage on saving throws against being frightened.

**Brute.** A melee weapon deals one extra die of its damage when Mr. Greystone hits with it (included in the attack).


---

### Actions

**Multiattack.** Mr. Greystone makes two melee attacks or two ranged attacks.

**Club.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Hand Crossbow.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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