---
type: pc
race: "Dragon"
class:
 - "Young Dragon Turtle"
subClass:
 - "CR 10"
cover: "Young Dragon Turtle.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/10
  - source/ftd
---
###### Young Dragon Turtle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Dragon Turtle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 178 (17d12 + 68) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 19 | 10 | 12 | 12 |
| **Mod** | +5 | +0 | +4 | +0 | +1 | +1 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Aquan, Draconic
**Saving Throws:** Dex +4, Con +8, Wis +5
**Damage Resistances:** fire

---

### Traits

**Amphibious.** The dragon turtle can breathe air and water.


---

### Actions

**Multiattack.** The dragon turtle makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 11 (1d12 + 5) piercing damage plus 6 (1d12) lightning damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.

**Steam Breath (Recharge 5–6).** The dragon turtle exhales steam in a 30-foot cone. Each creature in that area must make a DC 16 Constitution saving throw, taking 42 (12d6) fire damage on a failed save, or half as much damage on a successful one. Being underwater doesn't grant resistance against this damage.


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