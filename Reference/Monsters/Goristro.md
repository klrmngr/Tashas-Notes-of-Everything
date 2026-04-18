---
type: pc
race: "Fiend (demon)"
class:
 - "Goristro"
subClass:
 - "CR 17"
cover: "Goristro.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/17
  - source/mm
---
###### Goristro
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Goristro.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 310 (23d12 + 161) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 11 | 25 | 6 | 13 | 14 |
| **Mod** | +7 | +0 | +7 | -2 | +1 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Abyssal
**Saving Throws:** Str +13, Dex +6, Con +13, Wis +7
**Skills:** Perception +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Charge.** If the goristro moves at least 15 feet straight toward a target and then hits it with a gore attack on the same turn, the target takes an extra 38 (7d10) piercing damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be pushed up to 20 feet away and knocked prone.

**Labyrinthine Recall.** The goristro can perfectly recall any path it has traveled.

**Magic Resistance.** The goristro has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The goristro deals double damage to objects and structures.


---

### Actions

**Multiattack.** The goristro makes three attacks: two with its fists and one with its hoof.

**Fist.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage.

**Hoof.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 23 (3d10 + 7) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be knocked prone.

**Gore.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 45 (7d10 + 7) piercing damage.


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