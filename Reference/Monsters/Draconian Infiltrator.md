---
type: pc
race: "Monstrosity"
class:
 - "Draconian Infiltrator"
subClass:
 - "CR 3"
cover: "Draconian Infiltrator.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/ftd
---
###### Draconian Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconian Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 14 | 9 | 13 | 11 |
| **Mod** | +0 | +3 | +2 | -1 | +1 | +0 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Draconic
**Saving Throws:** Dex +5
**Skills:** Perception +3, Stealth +7
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Death Throes.** When the draconian is reduced to 0 hit points, it turns into a puddle of acid and splashes acid on those around it. Each creature within 5 feet of the draconian must succeed on a DC 12 Dexterity saving throw or be covered in acid for 1 minute. A creature can use its action to scrape or wash the acid off itself or another creature. A creature covered in the acid takes 7 (2d6) acid damage at the start of each of its turns.

**Glide.** When the draconian falls and isn't incapacitated, it subtracts up to 100 feet from the fall when calculating the fall's damage, and it can move up to 2 feet horizontally for every 1 foot it descends.


---

### Actions

**Multiattack.** The draconian makes two Dagger attacks. If both attacks hit the same creature, the target must succeed on a DC 12 Constitution saving throw or become poisoned until the end of the target's next turn. While poisoned in this way, the target is also paralyzed.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage.


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