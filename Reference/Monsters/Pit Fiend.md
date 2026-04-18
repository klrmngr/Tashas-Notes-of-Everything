---
type: pc
race: "Fiend (devil)"
class:
 - "Pit Fiend"
subClass:
 - "CR 20"
cover: "Pit Fiend.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/20
  - source/mm
---
###### Pit Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Pit Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 300 (24d10 + 168) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 24 | 22 | 18 | 24 |
| **Mod** | +8 | +2 | +7 | +6 | +4 | +7 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Dex +8, Con +13, Wis +10
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Fear Aura.** Any creature hostile to the pit fiend that starts its turn within 20 feet of the pit fiend must make a DC 21 Wisdom saving throw, unless the pit fiend is incapacitated. On a failed save, the creature is frightened until the start of its next turn. If a creature's saving throw is successful, the creature is immune to the pit fiend's Fear Aura for the next 24 hours.

**Magic Resistance.** The pit fiend has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The pit fiend's weapon attacks are magical.


---

### Actions

**Multiattack.** The pit fiend makes four attacks: one with its bite, one with its claw, one with its mace, and one with its tail.

**Bite.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 22 (4d6 + 8) piercing damage. The target must succeed on a DC 21 Constitution saving throw or become poisoned. While poisoned in this way, the target can't regain hit points, and it takes 21 (6d6) poison damage at the start of each of its turns. The poisoned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) slashing damage.

**Mace.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 15 (2d6 + 8) bludgeoning damage plus 21 (6d6) fire damage.

**Tail.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 24 (3d10 + 8) bludgeoning damage.


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