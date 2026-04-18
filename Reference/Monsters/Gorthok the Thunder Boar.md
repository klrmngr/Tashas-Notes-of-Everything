---
type: pc
race: "Monstrosity"
class:
 - "Gorthok the Thunder Boar"
subClass:
 - "CR 6"
cover: "Gorthok the Thunder Boar.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/6
  - source/dip
---
###### Gorthok the Thunder Boar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DIP
___

> [!infobox|no-t right]
> ![[Gorthok the Thunder Boar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 73 (7d12 + 28) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | DIP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 19 | 6 | 10 | 14 |
| **Mod** | +5 | +0 | +4 | -2 | +0 | +2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; thunder

---

### Traits

**Relentless (Recharges after a Short or Long Rest).** If Gorthok takes 27 damage or less that would reduce it to 0 hit points, it is reduced to 1 hit point instead.


---

### Actions

**Multiattack.** Gorthok makes two melee attacks: one with its lightning tusks and one with its thunder hooves.

**Lightning Tusks.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 7 (2d6) lightning damage.

**Thunder Hooves.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage plus 7 (2d6) thunder damage.

**Lightning Bolt (Recharge 6).** Gorthok shoots a bolt of lightning at one creature it can see within 120 feet of it. The target must make a DC 15 Dexterity saving throw, taking 18 (4d8) lightning damage on a failed save, or half as much damage on a successful one.


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