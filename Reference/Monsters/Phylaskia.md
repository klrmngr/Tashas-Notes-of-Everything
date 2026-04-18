---
type: pc
race: "Undead"
class:
 - "Phylaskia"
subClass:
 - "CR 9"
cover: "Phylaskia.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/9
  - source/mot
---
###### Phylaskia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Phylaskia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 18 | 10 | 16 | 14 |
| **Mod** | +5 | +2 | +4 | +0 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 17
**Languages:** all
**Saving Throws:** Con +8, Wis +7
**Skills:** Insight +7, Perception +7
**Damage Immunities:** necrotic; poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; poisoned

---

### Traits

**Gatekeeper's Aura.** Any creature that starts its turn within 10 feet of the phylaskia must make a DC 15 Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage on saving throws and its speed is halved until the start of its next turn.

**Undead Fortitude.** If damage reduces the phylaskia to 0 hit points, it must make a Constitution saving throw with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the phylaskia drops to 1 hit point instead.

**Vigilant.** The phylaskia can't be surprised.


---

### Actions

**Multiattack.** The phylaskia makes two longsword attacks and uses its Strength Drain once.

**Longsword.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage, or 16 (2d10 + 5) slashing damage if used with two hands, plus 11 (2d10) necrotic damage.

**Strength Drain.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 12 (2d6 + 5) necrotic damage. Unless the target is immune to necrotic damage, its Strength score is reduced by 1d4. The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.


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