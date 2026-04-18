---
type: pc
race: "Humanoid"
class:
 - "Warrior"
subClass:
 - "CR —"
cover: "Warrior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/sdw
---
###### Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SDW
___

> [!infobox|no-t right]
> ![[Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 20 (plate, shield) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | SDW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 10 | 12 | 10 |
| **Mod** | +4 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, plus one of your choice
**Saving Throws:** Con +6
**Skills:** Athletics +8, Perception +5, Survival +5

---

### Traits

**Battle Readiness.** The warrior has advantage on initiative rolls.

**Improved Critical.** The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the d20.

**Indomitable (1/Day).** The warrior can reroll a saving throw that it fails, but it must use the new result.

**Martial Role.** The warrior has one of the following traits of your choice:
- **Attacker.** The warrior gains a +2 bonus to attack rolls.
- **Defender.** The warrior gains the Protection reaction below.

**Second Wind (Recharges after a Short or Long Rest).** The warrior can use a bonus action on its turn to regain hit points equal to 1d10 + its level.


---

### Actions

**Extra Attack.** The warrior can attack twice, instead of once, whenever it takes the attack action on its turn.

**Longsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


---

### Reactions

**Protection (Defender Only).** When a creature the warrior can see attacks a target other than the warrior that is within 5 feet of the warrior, the warrior can use their reaction to impose disadvantage on the attack roll. The warrior must be wielding a shield.


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