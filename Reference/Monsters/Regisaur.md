---
type: pc
race: "Monstrosity (dinosaur)"
class:
 - "Regisaur"
subClass:
 - "CR 14"
cover: "Regisaur.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/14
  - source/bgg
---
###### Regisaur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Regisaur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (dinosaur) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 181 (11d20 + 66) |
> | :FasUserGroup: Race | Monstrosity (dinosaur) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 8 | 23 | 4 | 12 | 6 |
| **Mod** | +8 | -1 | +6 | -3 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Magic Resistance.** The regisaur has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The regisaur makes one Bite attack and one Tail attack. The regisaur can't target the same creature with both attacks.

**Bite.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 47 (6d12 + 8) piercing damage, and the target has the grappled condition (escape DC 18). Until this grapple ends, the target has the restrained condition, and the regisaur can't Bite another target.

**Tail.** Melee Weapon Attack: +13 to hit, reach 20 ft., one target. *Hit:* 26 (4d8 + 8) bludgeoning damage.


---

### Bonus Actions

**Swallow.** Melee Weapon Attack: +13 to hit, reach 5 ft., one Huge or smaller creature grappled by the regisaur. *Hit:* The regisaur swallows the target, and the grapple ends. A swallowed creature has the blinded and restrained conditions, it has 3 against attacks and other effects outside the regisaur, and it takes 7 (2d6) acid damage at the start of each of its turns. The regisaur can have up to two creatures swallowed at a time.
If the regisaur takes 25 damage or more on a single turn from a swallowed creature, the regisaur must succeed on a DC 16 Constitution saving throw at the end of that turn or regurgitate the creature, which falls in a space within 5 feet of the regisaur and has the prone condition; the creature no longer has the blinded and restrained conditions.


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