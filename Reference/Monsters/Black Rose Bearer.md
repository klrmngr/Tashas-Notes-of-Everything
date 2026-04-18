---
type: pc
race: "Undead"
class:
 - "Black Rose Bearer"
subClass:
 - "CR 6"
cover: "Black Rose Bearer.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/veor
---
###### Black Rose Bearer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Black Rose Bearer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 110 (13d8 + 52) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 6 | 18 | 2 | 10 | 5 |
| **Mod** | +3 | -2 | +4 | -4 | +0 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages it knew in life but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Berserk.** Whenever the bearer takes damage or makes a Strength or Dexterity saving throw, roll a d6. On a 5 or 6, the bearer goes berserk. On each of its turns while berserk, the bearer has advantage on melee attack rolls, it can Dash as a bonus action, and it must attack the nearest creature it can see. If no creature is near enough to move to and attack, the bearer attacks an object, with preference for an object smaller than itself. Once the bearer goes berserk, it remains berserk until it is destroyed or its creator gives it a pristine black rose.

**Undead Fortitude.** If damage reduces the bearer to 0 hit points, it must make a Constitution saving throw with a DC of 5 plus the damage taken, unless the damage is radiant or from a critical hit. On a successful save, the bearer drops to 1 hit point instead.


---

### Actions

**Multiattack.** The bearer makes two Slam attacks.

**Slam.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage plus 11 (2d10) necrotic damage.


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