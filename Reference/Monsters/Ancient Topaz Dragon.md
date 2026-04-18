---
type: pc
race: "Dragon (gem)"
class:
 - "Ancient Topaz Dragon"
subClass:
 - "CR 20"
cover: "Ancient Topaz Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/20
  - source/ftd
---
###### Ancient Topaz Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Ancient Topaz Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (gem) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 280 (17d20 + 102) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 23 | 20 | 19 | 20 |
| **Mod** | +6 | +1 | +6 | +5 | +4 | +5 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +7, Con +12, Wis +10, Cha +11
**Skills:** Intimidation +17, Perception +16, Stealth +7
**Damage Resistances:** cold; necrotic

---

### Traits

**Amphibious.** The dragon can breathe both air and water.

**Fabricate (1/Day).** The dragon can cast fabricate, requiring no spell components and using Intelligence as the spellcasting ability.

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage plus 10 (3d6) necrotic damage.

**Claw.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Desiccating Breath (Recharge 5–6).** The dragon exhales yellowish necrotic energy in a 90-foot cone. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, the creature takes 49 (14d6) necrotic damage and is weakened until the end of its next turn. A weakened creature has disadvantage on Strength-based ability checks and Strength saving throws, and the creature's weapon attacks that rely on Strength deal half damage. On a successful save, the creature takes half as much damage and isn't weakened.


---

### Bonus Actions

**Change Shape.** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it.

**Psychic Step.** The dragon magically teleports to an unoccupied space it can see within 60 feet of it.


---

### Legendary Actions

### 

**Claw.** The dragon makes one Claw attack.

**Psionics (Costs 2 Actions).** The dragon uses Psychic Step or Spellcasting.

**Essential Reduction (Costs 3 Actions).** The dragon targets a creature or an object not being worn or carried that it can see within 60 feet of it. The target must succeed on a DC 19 Constitution saving throw or take 40 (9d8) necrotic damage. If this damage reduces the target to 0 hit points, it crumbles to dust.


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