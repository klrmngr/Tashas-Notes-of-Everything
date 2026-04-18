---
type: pc
race: "Monstrosity"
class:
 - "Miasmorne"
subClass:
 - "CR 16"
cover: "Miasmorne.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/16
  - source/coa
---
###### Miasmorne
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Miasmorne.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 230 (20d12 + 100) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 21 | 3 | 10 | 10 |
| **Mod** | +6 | +0 | +5 | -4 | +0 | +0 |

**Speed:** 20 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** tremorsense 60 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Str +11, Con +10
**Skills:** Arcana +1, Athletics +16, Survival +5
**Damage Immunities:** acid; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** petrified

---

### Traits

**Acidic Attacks.** If a creature takes acid damage from the miasmorne and that creature is wearing nonmagical metal armor, that armor is destroyed.

**Acidic Hide.** After a nonmagical metal weapon hits the miasmorne that weapon melts and is destroyed. Likewise, nonmagical metal ammunition that hits the miasmorne is destroyed.


---

### Actions

**Multiattack.** The miasmorne makes three attacks using Bite, Flechette or a combination of the two.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) bludgeoning damage plus 7 (2d6) acid damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 18). The miasmorne can't make Bite attacks while a creature is grappled in this way.

**Flechette.** Ranged Weapon Attack: +11 to hit, range 60/120 ft., one target. *Hit:* 16 (3d6 + 6) acid damage.

**Flechette Spray (Recharge 5–6).** The miasmorne launches flechettes from its fins in a 90-foot cone in front of it. All creatures in the cone must make a DC 19 Dexterity saving throw, taking 21 (6d6) acid damage on a failed save, or half as much damage on a successful one.

**Acidic Secretion (1/Day).** The miasmorne secretes an acidic solution, then sprays it around itself. All creatures in a 20-foot-radius sphere, centered on the miasmorne, must make a DC 19 Dexterity saving throw. Targets take 26 (4d12) acid damage on a failed save, or half as much damage on a successful one. All nonmagical metals within the radius that aren't being carried, as well as nonmagical metal items carried or worn by creatures that failed the save, are destroyed.


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