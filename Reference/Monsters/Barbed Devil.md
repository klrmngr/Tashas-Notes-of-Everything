---
type: pc
race: "Fiend (devil)"
class:
 - "Barbed Devil"
subClass:
 - "CR 5"
cover: "Barbed Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/mm
---
###### Barbed Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Barbed Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 110 (13d8 + 52) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 18 | 12 | 14 | 14 |
| **Mod** | +3 | +3 | +4 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Str +6, Con +7, Wis +5, Cha +5
**Skills:** Deception +5, Insight +5, Perception +8
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Barbed Hide.** At the start of each of its turns, the barbed devil deals 5 (1d10) piercing damage to any creature grappling it.

**Devil's Sight.** Magical darkness doesn't impede the devil's darkvision.

**Magic Resistance.** The devil has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes three melee attacks: one with its tail and two with its claws. Alternatively, it can use Hurl Flame twice.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Tail.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage.

**Hurl Flame.** Ranged Spell Attack: +5 to hit, range 150 ft., one target. *Hit:* 10 (3d6) fire damage. If the target is a flammable object that isn't being worn or carried, it also catches fire.


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