---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Spitting Mimic"
subClass:
 - "CR 5"
cover: "Spitting Mimic.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/idrotf
---
###### Spitting Mimic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Spitting Mimic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 17 | 9 | 15 | 10 |
| **Mod** | +5 | +1 | +3 | -1 | +2 | +0 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Skills:** Stealth +7
**Damage Immunities:** acid
**Condition Immunities:** prone

---

### Traits

**Shapechanger.** The mimic can use its action to polymorph into an object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Adhesive (Object Form Only).** The mimic adheres to anything that touches it. A Huge or smaller creature adhered to the mimic is also grappled by it (escape DC 16). Ability checks made to escape this grapple have disadvantage.

**False Appearance (Object Form Only).** While the mimic remains motionless, it is indistinguishable from an ordinary object.

**Grappler.** The mimic has advantage on attack rolls against any creature grappled by it.

**Magic Resistance.** The mimic has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The mimic attacks three times: twice with its pseudopods and once with its bite.

**Pseudopods.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage. If the mimic is in object form, the target is subjected to its Adhesive trait.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 10 (1d10 + 5) piercing damage plus 7 (2d6) acid damage.

**Spit Acid (Recharge 5–6).** The mimic spits acid at one creature it can see within 30 feet of it. The target must make a DC 14 Dexterity saving throw, taking 32 (9d6 + 1) acid damage on failed save, or half as much damage on a successful one.


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