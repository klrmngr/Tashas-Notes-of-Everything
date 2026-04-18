---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Yagnoloth"
subClass:
 - "CR 11"
cover: "Yagnoloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/mpmm
---
###### Yagnoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Yagnoloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend (yugoloth) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 147 (14d10 + 70) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 21 | 16 | 15 | 18 |
| **Mod** | +4 | +2 | +5 | +3 | +2 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 16
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Saving Throws:** Dex +6, Int +7, Wis +6, Cha +8
**Skills:** Deception +8, Insight +6, Perception +6, Persuasion +8
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The yagnoloth has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yagnoloth makes one Electrified Touch attack and one Massive Arm attack, or it makes one Massive Arm attack and uses Battlefield Cunning, if available, or Teleport.

**Electrified Touch.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 27 (6d8) lightning damage.

**Massive Arm.** Melee Weapon Attack: +8 to hit, reach 15 ft., one target. *Hit:* 23 (3d12 + 4) force damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or become stunned until the end of the yagnoloth's next turn.

**Battlefield Cunning (Recharge 4–6).** Up to two allied yugoloths within 60 feet of the yagnoloth that can hear it can use their reactions to make one melee attack each.

**Life Leech.** The yagnoloth touches one incapacitated creature within 15 feet of it. The target takes 36 (7d8 + 4) necrotic damage, and the yagnoloth gains temporary hit points equal to half the damage dealt. The target must succeed on a DC 16 Constitution saving throw, or its hit point maximum is reduced by an amount equal to half the necrotic damage taken. This reduction lasts until the target finishes a long rest, and the target dies if its hit point maximum is reduced to 0.

**Teleport.** The yagnoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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