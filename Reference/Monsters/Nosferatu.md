---
type: pc
race: "Undead"
class:
 - "Nosferatu"
subClass:
 - "CR 8"
cover: "Nosferatu.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/8
  - source/vrgr
---
###### Nosferatu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Nosferatu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 85 (9d8 + 45) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 18 | 21 | 6 | 17 | 14 |
| **Mod** | +5 | +4 | +5 | -2 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** the languages it knew in life
**Saving Throws:** Dex +7, Con +8, Wis +6
**Skills:** Perception +6, Stealth +10
**Damage Resistances:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Regeneration.** The nosferatu regains 10 hit points at the start of each of its turns if it has at least 1 hit point and isn't in sunlight. If the nosferatu takes radiant damage, this trait doesn't function until the start of the nosferatu's next turn.

**Spider Climb.** The nosferatu can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Hypersensitivity.** The nosferatu takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

**Unusual Nature.** The nosferatu doesn't require air.


---

### Actions

**Multiattack.** The nosferatu makes two Claw attacks followed by one Bite attack. If both Claw attacks hit the same creature, the Bite attack is made with advantage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 9 (1d8 + 5) piercing damage plus 7 (2d6) necrotic damage. If the target is missing any of its hit points, it instead takes 11 (2d10) necrotic damage.
The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the nosferatu regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain in this way and then buried in the ground rises as a nosferatu after 1d10 days.

**Blood Disgorge (Recharge 5–6).** The nosferatu vomits blood in a 15-foot cone. Each creature in that area must make a DC 16 Constitution saving throw. On a failed save, a creature takes 18 (4d8) necrotic damage, and it can't regain hit points for 1 minute. On a successful save, the creature takes half as much damage with no additional effects.


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