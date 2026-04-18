---
type: pc
race: "Dragon (wizard)"
class:
 - "Velomachus Lorehold"
subClass:
 - "CR 25"
cover: "Velomachus Lorehold.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/25
  - source/scc
---
###### Velomachus Lorehold
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Velomachus Lorehold.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (wizard) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 487 (25d20 + 225) |
> | :FasUserGroup: Race | Dragon (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 14 | 29 | 30 | 20 | 18 |
| **Mod** | +10 | +2 | +9 | +10 | +5 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 23
**Languages:** all
**Saving Throws:** Dex +10, Con +17, Wis +13, Cha +12
**Skills:** Arcana +18, History +18, Investigation +18, Perception +13
**Damage Immunities:** thunder

---

### Traits

**Legendary Resistance (3/Day).** If Velomachus fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Velomachus makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +18 to hit, reach 15 ft., one target. *Hit:* 15 (1d10 + 10) piercing damage plus 6 (1d12) thunder damage.

**Claw.** Melee Weapon Attack: +18 to hit, reach 10 ft., one target. *Hit:* 13 (1d6 + 10) slashing damage. If the target is a Huge or smaller creature, it is knocked prone.

**Battle Tide Breath (Recharge 5–6).** Velomachus exhales thunderous sound in a 90-foot cone. Each creature in that area must make a DC 25 Constitution saving throw. On a failure, a creature takes 45 (7d12) force damage and 45 (7d12) thunder damage and is pushed up to 20 feet in a horizontal direction of Velomachus' choice. On a success, the creature takes half as much damage and isn't pushed. Objects that aren't being worn or carried take the damage and are pushed as if they were creatures that failed the saving throw.


---

### Legendary Actions

### 

**Claw.** Velomachus makes one Claw attack.

**Chaotic Flow (Costs 2 Actions).** Velomachus moves up to half her flying speed. If a creature hits or misses her with an opportunity attack during this move, the attacker takes 19 (3d12) thunder damage.

**Repeating History (Costs 3 Actions).** Velomachus magically summons 1d4 [[Spirit Statue Mascot|statue mascots]] in unoccupied spaces she can see within 60 feet of herself. The spirit statues obey her commands and take their turns immediately after hers. Any creature, other than a spirit statue or Velomachus, is restrained if it starts its turn within 5 feet of one or more of these spirit statues. This restrained condition lasts until the end of the creature's turn. These spirit statues disappear after 10 minutes, when Velomachus dies, or when she uses this action again.


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