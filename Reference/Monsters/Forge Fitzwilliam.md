---
type: pc
race: "Humanoid"
class:
 - "Forge Fitzwilliam"
subClass:
 - "CR 8"
cover: "Forge Fitzwilliam.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/hat-tg
---
###### Forge Fitzwilliam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Honor Among Thieves: Thieves' Gallery
___

> [!infobox|no-t right]
> ![[Forge Fitzwilliam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (disarming charm) |
> | :FasHeart: HP | 110 (20d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Honor Among Thieves: Thieves' Gallery |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 13 | 15 | 17 | 20 |
| **Mod** | +0 | +2 | +1 | +2 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +5, Int +5
**Skills:** Acrobatics +5, Deception +11, Investigation +8, Persuasion +11, Sleight Of Hand +5, Stealth +8

---

### Traits

**Disarming Charm.** While Forge isn't wearing armor, his AC includes his Charisma modifier.

**Double-Cross.** If Forge hits a creature friendly to him with an attack roll, the attack is automatically a critical hit.

**Evasion.** If Forge is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, he takes no damage if he succeeds on the saving throw, and only half damage if he fails, provided he isn't incapacitated.


---

### Actions

**Multiattack.** Forge makes two Dagger attacks, two Heavy Crossbow attacks, or one of each.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 24 (7d6) poison damage, and the target is poisoned until the end of its next turn.

**Heavy Crossbow.** Ranged Weapon Attack: +5 to hit, range 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 24 (7d6) poison damage. If the target is a creature, it has disadvantage on the next attack roll it makes before the start of Forge's next turn.


---

### Bonus Actions

**Cunning.** Forge takes the Dash, Disengage, or Hide action, or he gives himself advantage on the next attack roll he makes before the end of this turn.


---

### Reactions

**Uncanny Dodge.** Forge halves the damage he takes from an attack that hits him. He must be able to see the attacker.


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