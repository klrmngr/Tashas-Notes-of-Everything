---
type: pc
race: "Fiend (devil)"
class:
 - "Nergaliid"
subClass:
 - "CR 3"
cover: "Nergaliid.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/3
  - source/egw
---
###### Nergaliid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Nergaliid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 42 (4d10 + 20) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 20 | 12 | 10 | 12 |
| **Mod** | +4 | +1 | +5 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Common, Infernal
**Skills:** Deception +5, Perception +2, Stealth +5
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Shadow Stealth.** While in dim light or darkness, the nergaliid can take the Hide action as a bonus action.

**Standing Leap.** The nergaliid's long jump is up to 30 feet and its high jump is up to 20 feet, with or without a running start.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 13 (2d8 + 4) piercing damage, and the target must succeed on a DC 15 Constitution saving throw or become poisoned for 1 minute. The poisoned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tongue Lash.** Melee Weapon Attack: +6 to hit, reach 20 ft., one target. *Hit:* 10 (1d12 + 4) bludgeoning damage.

**Siphon Life (Recharge 4–6).** The nergaliid magically draws the life from a humanoid it can see within 40 feet of it. The target must make a DC 15 Wisdom saving throw. An incapacitated target fails the save automatically. On a failed save, the creature takes 10 (3d6) psychic damage, and the nergaliid gains temporary hit points equal to the damage taken. On a successful save, the target takes half as much damage, and the nergaliid doesn't gain temporary hit points. If this damage kills the target, its body rises at the end of the nergaliid's current turn as a [[Husk Zombie]] (see earlier in this chapter).


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