---
type: pc
race: "Monstrosity"
class:
 - "Nightmare Beast"
subClass:
 - "CR 16"
cover: "Nightmare Beast.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/16
  - source/mcv1sc
---
###### Nightmare Beast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV1SC
___

> [!infobox|no-t right]
> ![[Nightmare Beast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 232 (15d20 + 75) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV1SC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 21 | 9 | 12 | 15 |
| **Mod** | +8 | +0 | +5 | -1 | +1 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** understands the languages of its creator but can't speak

---

### Traits

**Legendary Resistance (2/Day).** If the beast fails a saving throw, it can choose to succeed instead.

**Siege Monster.** The beast deals double damage to objects and structures.


---

### Actions

**Multiattack.** The beast makes two Claw attacks and one Tusk attack.

**Claw.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 14 (1d12 + 8) slashing damage, and if the target is a creature, it must succeed on a DC 21 Strength saving throw or be knocked prone.

**Tusk.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 17 (2d8 + 8) slashing damage.

**Disintegration Gaze (Recharge 5–6).** The beast targets one creature it can see within 60 feet of itself. The target must make a DC 18 Constitution saving throw, taking 70 (10d6 + 40) force damage on a failed save, or half as much damage on a successful one. If this magical effect reduces the target to 0 hit points, the target is disintegrated and leaves nothing behind, except a pile of ashes plus whatever equipment it was wearing or carrying.


---

### Bonus Actions

**Teleport (2/Day).** The beast magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


---

### Legendary Actions

### 

**Tusk Attack.** The beast makes one Tusk attack.

**Charge (Costs 2 Actions).** The beast moves up to its speed without provoking opportunity attacks, then makes two Tusk attacks.

**Frightful Howl (Costs 2 Actions).** The beast howls as it exhales a cloud of magical fear gas in a 120-foot cone. Any creature in that area must succeed on a DC 18 Wisdom saving throw or be frightened of the beast for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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