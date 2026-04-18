---
type: pc
race: "Undead"
class:
 - "Deathless Rider"
subClass:
 - "CR 5"
cover: "Deathless Rider.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/mcv4ec
---
###### Deathless Rider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Deathless Rider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 14 | 6 | 6 | 5 |
| **Mod** | +4 | +0 | +2 | -2 | -2 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Str +7, Con +5
**Skills:** Athletics +7, Perception +1
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Mounted Adept.** While mounted and without the incapacitated condition, the rider has advantage on melee attack rolls against any unmounted creature smaller than its mount, the rider and its mount have advantage on Dexterity saving throws, and the rider can force an attack targeted at its mount to target the rider instead.

**Undead Fortitude.** If damage reduces the rider to 0 hit points, it must make a Constitution saving throw with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the rider drops to 1 hit point instead.


---

### Actions

**Multiattack.** The rider makes two Axe attacks. It can replace one of these attacks with Fell Glare.

**Axe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Fell Glare.** The rider gazes at a creature within 30 feet of itself. The creature must succeed on a DC 13 Wisdom saving throw or have the frightened condition for 1 minute. The frightened creature can repeat the saving throw at the end of each of its turns, with disadvantage if it can see the rider, ending the condition on itself on a success.


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