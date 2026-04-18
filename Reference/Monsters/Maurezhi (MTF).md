---
type: pc
race: "Fiend (demon)"
class:
 - "Maurezhi"
subClass:
 - "CR 7"
cover: "Maurezhi.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/7
  - source/mtf
---
###### Maurezhi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Maurezhi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 12 | 11 | 12 | 15 |
| **Mod** | +2 | +3 | +1 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, Elvish, telepathy 120 ft.
**Skills:** Deception +5
**Damage Resistances:** cold; fire; lightning; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Assume Form.** The maurezhi can assume the appearance of any Medium humanoid it has eaten. It remains in this form for 1d6 days, during which time the form gradually decays until, when the effect ends, the form sloughs from the demon's body.

**Magic Resistance.** The maurezhi has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The maurezhi makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage. If the target is a humanoid, its Charisma score is reduced by 1d4. This reduction lasts until the target finishes a short or long rest. The target dies if this reduces its Charisma to 0. It rises 24 hours later as a ghoul, unless it has been revived or its corpse has been destroyed.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage. If the target is a creature other than an undead, it must succeed on a DC 12 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Raise Ghoul (Recharge 5–6).** The maurezhi targets one dead ghoul or ghast it can see within 30 feet of it. The target is revived with all its hit points.


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