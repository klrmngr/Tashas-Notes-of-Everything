---
type: pc
race: "Humanoid (kenku, warlock)"
class:
 - "Kettlesteam the Kenku"
subClass:
 - "CR 1"
cover: "Kettlesteam the Kenku.png"
campaign:
locations:
tags:
  - race/kenku
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/wbtw
---
###### Kettlesteam the Kenku
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Kettlesteam the Kenku.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (kenku, warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (kenku, warlock) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 10 | 11 | 10 | 16 |
| **Mod** | +0 | +3 | +0 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** understands Auran and Common but speaks only through the use of her Mimicry trait
**Saving Throws:** Wis +2, Cha +5
**Skills:** Arcana +2, Deception +5, Investigation +2, Perception +2, Persuasion +5, Stealth +5

---

### Traits

**Mimicry.** Kettlesteam can mimic any sounds she has heard, including voices. A creature that hears the sounds can tell they are imitations only with a successful DC 13 Wisdom (Insight) check.


---

### Actions

**Multiattack.** Kettlesteam makes two Dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Twilight Sleep (2/Day).** Kettlesteam targets one creature she can see within 10 feet of her. The target is engulfed in a cloud of magical, sleep-inducing gas and must succeed on a DC 13 Constitution saving throw or fall unconscious for 1 minute. A creature put to sleep by this gas awakens instantly if it takes damage, or if someone uses an action to shake or slap the sleeper awake.


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