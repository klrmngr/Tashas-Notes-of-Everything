---
type: pc
race: "Fiend"
class:
 - "Hellcat (Bezekira)"
subClass:
 - "CR 10"
cover: "Hellcat (Bezekira).png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/10
  - source/coa
---
###### Hellcat (Bezekira)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Hellcat (Bezekira).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 19 | 17 | 10 | 14 | 10 |
| **Mod** | +5 | +4 | +3 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 16
**Languages:** understands Infernal, telepathy 120 ft.
**Saving Throws:** Dex +8, Con +7
**Skills:** Acrobatics +8, Athletics +9, Perception +6, Stealth +12
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered; 
**Damage Immunities:** fire

---

### Traits

**Darkness Dweller.** Attacks made against a bezekira in bright or dim light have disadvantage.

**Devil's Sight.** Magical darkness doesn't impede the bezekira's darkvision.


---

### Actions

**Multiattack.** The bezekira makes three Claw attacks. It can replace one of the attacks with a Bite attack.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage plus 7 (2d6) fire damage. The bezekira deals an extra 28 (8d6) fire damage when it hits a target with an attack and has advantage on the attack roll.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) bludgeoning damage, grasping the target with its mouth. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 17). The bezekira can't make a Bite attack while a creature is grappled in this way.


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