---
type: pc
race: "Monstrosity"
class:
 - "Polukranos"
subClass:
 - "CR 19"
cover: "Polukranos.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/19
  - source/mot
---
###### Polukranos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Polukranos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 232 (15d20 + 75) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 15 | 21 | 4 | 14 | 10 |
| **Mod** | +7 | +2 | +5 | -3 | +2 | +0 |

**Speed:** 50 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 24
**Languages:** —
**Skills:** Perception +14
**Damage Immunities:** acid

---

### Traits

**Acidic Blood.** When Polukranos takes piercing or slashing damage, each creature within 5 feet of Polukranos takes 10 (3d6) acid damage.

**Hold Breath.** Polukranos can hold its breath for 1 hour.

**Legendary Resistance (3/Day).** If Polukranos fails a saving throw, it can choose to succeed instead.

**Multiple Heads.** Polukranos has five heads. While it has more than one head, Polukranos has advantage on saving throws against being blinded, charmed, deafened, frightened, stunned, or knocked unconscious. Whenever Polukranos takes 40 or more damage in a single turn, one of its heads dies. If all its heads die, Polukranos dies. At the end of its turn, it grows two heads for each of its heads that died since its last turn, unless it has taken 40 or more fire damage since its last turn. Polukranos regains 20 hit points for each head regrown in this way.

**Reactive Heads.** For each head Polukranos has beyond one, it gets an extra reaction that can be used only to make opportunity attacks.

**Siege Monster.** Polukranos deals double damage to objects and structures.

**Wakeful.** While Polukranos sleeps, at least one of its heads is awake.


---

### Actions

**Multiattack.** Polukranos makes as many bite attacks as it has heads.

**Bite.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage.

**Stomp.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 16 (2d8 + 7) bludgeoning damage.

**Tail.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 18 (2d10 + 7) bludgeoning damage. If the target is a creature, it must succeed on a DC 21 Strength saving throw or be pushed up to 20 feet away from Polukranos.


---

### Legendary Actions

### 

**Detect.** Polukranos makes a Wisdom (Perception) check.

**Tail Swipe.** Polukranos makes a tail attack.

**Trampling Charge (Costs 3 Actions).** Polukranos moves up to 50 feet in a straight line and can move through the space of any creature Huge or smaller. The first time it enters each creature's space during this move, it can make a stomp attack against that creature.


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