---
type: pc
race: "Undead (warlock)"
class:
 - "Deathlock Wight"
subClass:
 - "CR 3"
cover: "Deathlock Wight.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/mpmm
---
###### Deathlock Wight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Deathlock Wight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Undead (warlock) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 16 | 12 | 14 | 16 |
| **Mod** | +0 | +2 | +3 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** the languages it knew in life
**Saving Throws:** Wis +4
**Skills:** Arcana +3, Perception +4
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the deathlock has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Unusual Nature.** The deathlock doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The deathlock makes two Life Drain or Grave Bolt attacks.

**Life Drain.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 6 (1d8 + 2) necrotic damage. The target must succeed on a DC 13 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.
A Humanoid slain by this attack rises 24 hours later as a zombie under the deathlock's control, unless the Humanoid is restored to life or its body is destroyed. The deathlock can have no more than twelve zombies under its control at one time.

**Grave Bolt.** Ranged Spell Attack: +5 to hit, range 60 ft., one target. *Hit:* 12 (2d8 + 3) necrotic damage.


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