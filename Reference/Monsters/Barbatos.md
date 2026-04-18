---
type: pc
race: "Humanoid (human)"
class:
 - "Barbatos"
subClass:
 - "CR 6"
cover: "Barbatos.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/imr
---
###### Barbatos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Barbatos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 13 | 14 | 10 |
| **Mod** | +0 | +3 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Skills:** Animal Handling +5, Deception +3, Perception +5, Stealth +6
**Damage Resistances:** poison

---

### Traits

**Rust Monster Cloak.** Any nonmagical weapon made of metal that hits Barbatos corrodes. After dealing damage, the weapon takes a permanent and cumulative -1 penalty to damage rolls. If its penalty drops to -5, the weapon is destroyed. Nonmagical ammunition made of metal that hits Barbatos is destroyed after dealing damage.

**Heart of the Troll.** Barbatos regains 10 hit points at the start of his turn. If Barbatos takes acid or fire damage, this trait doesn't function at the start of Barbatos's next turn. Barbatos dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Barbatos makes two bone shortsword attacks.

**Bone Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Light Crossbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned for 1 hour. If the saving throw fails by 5 or more, the target is also unconscious. The target regains consciousness if it takes damage or if another creature takes an action to shake it.

**Cloak Sweep.** Barbatos corrodes a nonmagical ferrous metal object he can see within 5 feet of himself. If the object isn't being worn or carried, the touch destroys a 1-foot cube of it. If the object is being worn or carried by a creature, the creature can make a DC 12 Dexterity saving throw to avoid Barbatos's touch.
If the object touched is either metal armor or a metal shield being worn or carried, it takes a permanent and cumulative 1 penalty to the AC it offers. Armor reduced to an AC of 10 or a shield that drops to a +0 bonus is destroyed. If the object touched is a held metal weapon, it rusts as described in Barbatos's Rust Monster Cloak trait.


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