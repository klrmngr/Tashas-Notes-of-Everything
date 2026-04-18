---
type: pc
race: "Dragon (druid)"
class:
 - "Beledros Witherbloom"
subClass:
 - "CR 24"
cover: "Beledros Witherbloom.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/24
  - source/scc
---
###### Beledros Witherbloom
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Beledros Witherbloom.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (druid) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 444 (24d20 + 192) |
> | :FasUserGroup: Race | Dragon (druid) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 14 | 27 | 18 | 28 | 17 |
| **Mod** | +9 | +2 | +8 | +4 | +9 | +3 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 26
**Languages:** Common, Draconic, Druidic, Sylvan
**Saving Throws:** Dex +9, Con +15, Wis +16, Cha +10
**Skills:** Arcana +18, Medicine +16, Nature +18, Perception +16
**Damage Immunities:** necrotic; poison
**Condition Immunities:** poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Beledros fails a saving throw, she can choose to succeed instead.

**Unusual Nature.** Beledros doesn't require air, food, or drink.


---

### Actions

**Multiattack.** Beledros makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 14 (1d10 + 9) piercing damage plus 6 (1d12) necrotic damage.

**Claw.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 12 (1d6 + 9) slashing damage. If the target is a Huge or smaller creature, it is knocked prone.

**Decaying Breath (Recharge 5–6).** Beledros exhales decaying energy in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw, taking 39 (6d12) necrotic damage and 39 (6d12) poison damage on a failed save, or half as much damage on a successful one. A creature that takes damage from the breath can't regain hit points until the start of Beledros's next turn.

**Miasmal Flow.** Beledros becomes a swirling cloud of green mist and can move up to half her flying speed without provoking opportunity attacks, then resumes her true form. During this movement, she can move through creatures and objects as if they were 3. If she moves through a creature, it must succeed on a DC 23 Constitution saving throw or become poisoned until the end of its next turn. If Beledros ends this move inside an object, she takes 5 (1d10) force damage and is shunted to the nearest unoccupied space.


---

### Legendary Actions

### 

**Claw.** Beledros makes one Claw attack.

**Miasmal Flow (Costs 2 Actions).** Beledros uses Miasmal Flow.

**Teeming with Life (Costs 3 Actions).** Beledros magically summons 1d4 pest mascots in unoccupied spaces she can see within 60 feet of herself. The pests obey her commands and take their turns immediately after hers. Any creature, other than a pest, takes 9 (2d8) poison damage if it starts its turn within 5 feet of one or more of these pests. When one of these pests drops to 0 hit points, Beledros regains 9 hit points. These pests disappear after 10 minutes, when Beledros dies, or when she uses this action again.


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