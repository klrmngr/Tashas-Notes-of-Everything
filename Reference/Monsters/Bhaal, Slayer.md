---
type: pc
race: "Humanoid"
class:
 - "Bhaal, Slayer"
subClass:
 - "CR 20"
cover: "Bhaal, Slayer.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/20
  - source/mabjov
---
###### Bhaal, Slayer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Bhaal, Slayer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 266 (28d8 + 140) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 22 | 20 | 14 | 16 | 14 |
| **Mod** | +7 | +6 | +5 | +2 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Abyssal, Common
**Saving Throws:** Str +13, Dex +12
**Skills:** Stealth +18
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; incapacitated; paralyzed; petrified; poisoned; stunned; unconscious

---

### Traits

**Assassinate.** During its first turn, the slayer has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the slayer scores against a surprised creature is a critical hit.

**Devil's Sight.** Magical darkness doesn't impede the slayer's darkvision.

**Immutable Form.** The slayer is immune to any spell or effect that would alter its form, except for its Ravager Form ability.

**Legendary Resistance (2/Day).** If the slayer fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The slayer has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The slayer's claw attacks are magical.


---

### Actions

**Multiattack.** The slayer makes four Claw attacks.

**Claw.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 16 (2d8 + 7) slashing damage plus 3 (1d6) necrotic damage. If the target is a creature, it must succeed on a DC 19 Constitution saving throw or have its hit point maximum reduced by an amount equal to the damage taken. The target dies if this attack reduces its hit point maximum to 0. The reduction lasts until removed by the greater restoration spell or other magic.


---

### Bonus Actions

**Prey.** The slayer focuses on a single creature it can see within 60 feet. Afterwards, the first time each turn that the slayer hits that creature, the slayer does an additional 7 (2d6) damage.


---

### Legendary Actions

### 

**Savage Disengage.** The slayer disengages without provoking opportunity attacks. If it moves within 5 feet of a creature it makes a Claw attack against the creature.

**Finish (Costs 2 Actions).** The slayer attacks a creature that has been marked by its Prey ability. If this attack hits and the creature has less than 40 hit points remaining after the attack, the creature is reduced to 0 hit points.

**Ravager Form (Costs 3 Actions).** If the slayer has killed a creature of CR/level 5 or greater that it previously marked with its Prey ability in the last minute, it can transform into its [[Bhaal, Ravager|ravager form]]. The form lasts until dawn (minimum 1 hour).


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