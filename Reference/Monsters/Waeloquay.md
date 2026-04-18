---
type: pc
race: "Elemental"
class:
 - "Waeloquay"
subClass:
 - "CR 18"
cover: "Waeloquay.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/18
  - source/coa
---
###### Waeloquay
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Waeloquay.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 290 (20d20 + 80) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 18 | 8 | 10 | 12 |
| **Mod** | +8 | +2 | +4 | -1 | +0 | +1 |

**Speed:** 30 ft., swim 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Aquan, Common
**Saving Throws:** Wis +6, Cha +7
**Skills:** Athletics +14, Nature +5
**Damage Resistances:** acid; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Magic Resistance.** Waeloquay has advantage on saving throws against spells and other magical effects.

**Legendary Resistance (3/Day).** If Waeloquay fails a saving throw, he can choose to succeed instead.

**Water Form.** Waeloquay can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Multiattack.** Waeloquay makes three Slam attacks.

**Slam.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 26 (4d8 + 8) bludgeoning damage.

**Whelm (Recharge 4–6).** Each creature in Waeloquay's space must make a DC 22 Strength saving throw. On a failed save, a target takes 21 (3d8 + 8) bludgeoning damage. If it is Large or smaller, it also has the grappled condition (escape DC 20). Until this grapple ends, the target is restrained and unable to breathe, unless it can breathe water. If the save is successful, the target is pushed out of Waeloquay's space. Waeloquay can grapple one Large creature or up to four Medium or smaller creatures at one time. At the start of each of Waeloquay's turns, each target grappled by it takes 21 (3d8 + 8) bludgeoning damage. A creature within 5 feet of Waeloquay can pull a creature or object out of it by taking an action to make a DC 22 Strength check and succeeding.


---

### Legendary Actions

### 

**Flow.** Waeloquay moves up to its speed.

**Crush (Costs 2 Actions).** One creature that Waeloquay is grappling takes 44 (8d8 + 8) bludgeoning damage.

**Pummel (Costs 2 Actions).** Waeloquay makes a Slam attack with advantage.


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