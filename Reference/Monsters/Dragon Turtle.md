---
type: pc
race: "Dragon"
class:
 - "Dragon Turtle"
subClass:
 - "CR 17"
cover: "Dragon Turtle.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/17
  - source/mm
---
###### Dragon Turtle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Dragon Turtle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 341 (22d20 + 110) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 20 | 10 | 12 | 12 |
| **Mod** | +7 | +0 | +5 | +0 | +1 | +1 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Aquan, Draconic
**Saving Throws:** Dex +6, Con +11, Wis +7
**Damage Resistances:** fire

---

### Traits

**Amphibious.** The dragon turtle can breathe air and water.


---

### Actions

**Multiattack.** The dragon turtle makes three attacks: one with its bite and two with its claws. It can make one tail attack in place of its two claw attacks.

**Bite.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 26 (3d12 + 7) piercing damage.

**Claw.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 16 (2d8 + 7) slashing damage.

**Tail.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 26 (3d12 + 7) bludgeoning damage. If the target is a creature, it must succeed on a DC 20 Strength saving throw or be pushed up to 10 feet away from the dragon turtle and knocked prone.

**Steam Breath (Recharge 5–6).** The dragon turtle exhales scalding steam in a 60-foot cone. Each creature in that area must make a DC 18 Constitution saving throw, taking 52 (15d6) fire damage on a failed save, or half as much damage on a successful one. Being underwater doesn't grant resistance against this damage.


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