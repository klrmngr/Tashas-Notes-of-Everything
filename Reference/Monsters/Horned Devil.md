---
type: pc
race: "Fiend (devil)"
class:
 - "Horned Devil"
subClass:
 - "CR 11"
cover: "Horned Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/mm
---
###### Horned Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Horned Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 178 (17d10 + 85) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 17 | 21 | 12 | 16 | 17 |
| **Mod** | +6 | +3 | +5 | +1 | +3 | +3 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Str +10, Dex +7, Wis +7, Cha +7
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the devil's darkvision.

**Magic Resistance.** The devil has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes three melee attacks: two with its fork and one with its tail. It can use Hurl Flame in place of any melee attack.

**Fork.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage.

**Tail.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 10 (1d8 + 6) piercing damage. If the target is a creature other than an undead or a construct, it must succeed on a DC 17 Constitution saving throw or lose 10 (3d6) hit points at the start of each of its turns due to an infernal wound. Each time the devil hits the wounded target with this attack, the damage dealt by the wound increases by 10 (3d6). Any creature can take an action to stanch the wound with a successful DC 12 Wisdom (Medicine) check. The wound also closes if the target receives magical healing.

**Hurl Flame.** Ranged Spell Attack: +7 to hit, range 150 ft., one target. *Hit:* 14 (4d6) fire damage. If the target is a flammable object that isn't being worn or carried, it also catches fire.


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