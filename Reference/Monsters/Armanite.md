---
type: pc
race: "Fiend (demon)"
class:
 - "Armanite"
subClass:
 - "CR 7"
cover: "Armanite.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/7
  - source/mpmm
---
###### Armanite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Armanite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 18 | 21 | 8 | 12 | 13 |
| **Mod** | +5 | +4 | +5 | -1 | +1 | +1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, telepathy 120 ft.
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The armanite has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The armanite makes one Claw attack, one Hooves attack, and one Serrated Tail attack.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 10 (2d4 + 5) slashing damage plus 9 (2d8) lightning damage.

**Hooves.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 16 Strength saving throw or be knocked prone.

**Serrated Tail.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) slashing damage.

**Lightning Lance (Recharge 5–6).** The armanite looses a bolt of lightning in a line that is 60 feet long and 10 feet wide. Each creature in the line must make a DC 15 Dexterity saving throw, taking 36 (8d8) lightning damage on a failed save, or half as much damage on a successful one.


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