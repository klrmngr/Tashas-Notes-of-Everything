---
type: pc
race: "Fey"
class:
 - "Nintra Siotta"
subClass:
 - "CR 16"
cover: "Nintra Siotta.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/16
  - source/cm
---
###### Nintra Siotta
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Nintra Siotta.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 306 (36d10 + 108) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 24 | 16 | 17 | 15 | 24 |
| **Mod** | +3 | +7 | +3 | +3 | +2 | +7 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 17
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Str +8, Dex +12, Wis +7
**Skills:** Deception +12, Insight +7, Perception +7
**Condition Immunities:** charmed; exhaustion; stunned

---

### Traits

**Legendary Resistance (3/Day).** If Nintra fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Nintra makes two attacks.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 12 (2d4 + 7) piercing damage.

**Shard of Shadow.** Ranged Spell Attack: +12 to hit, range 120 ft., one target. *Hit:* 10 (1d6 + 7) necrotic damage, and if the target is a creature, it must succeed on a DC 20 Constitution saving throw or be poisoned until the end of its next turn.

**Storm of Shattered Glass (Recharge 6).** Nintra targets a point she can see within 60 feet of her and creates a 20-foot-radius sphere of swirling glass shards centered on that point. Each creature in the sphere must make a DC 20 Dexterity saving throw, taking 28 (8d6) slashing damage on a failed save, or half as much damage on a successful save. If Nintra is in the sphere, the shards deal no damage to her.


---

### Legendary Actions

### 

**Attack.** Nintra makes one attack.

**Fey Step.** Nintra teleports to an unoccupied space she can see within 30 feet of her.

**Shadow Strikes (Costs 2 Actions).** Provided she is in bright or dim light, Nintra causes her shadow to attack a creature within 10 feet of her. Her shadow makes two claw attacks, each attack identical to Nintra's claw attack except that it deals psychic damage instead of piercing damage.


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