---
type: pc
race: "Fiend (devil)"
class:
 - "Affliction Devil (Kocrachon)"
subClass:
 - "CR 10"
cover: "Affliction Devil (Kocrachon).png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/10
  - source/coa
---
###### Affliction Devil (Kocrachon)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Affliction Devil (Kocrachon).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 15 | 17 | 12 | 14 |
| **Mod** | +3 | +4 | +2 | +3 | +1 | +2 |

**Speed:** 30 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Infernal, telepathy 120 ft.
**Saving Throws:** Dex +8, Int +7
**Skills:** Deception +6, Intimidation +6, Perception +5, Stealth +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the kocrachon's darkvision.

**Infernal Rot.** A creature afflicted with this disease has the poisoned condition until the disease ends. While diseased, creatures gain no benefits from a long rest, gaining exhaustion when necessary. If a creature dies while afflicted with Infernal Rot, its corpse transforms into a newborn kocrachon after 4 (1d8) days.

**Magic Resistance.** The kocrachon has advantage on saving throws against spells and other magical effects.

**Sadism.** The kocrachon gains a +1 bonus to attack and damage rolls for each different creature it damaged on its previous turn.


---

### Actions

**Multiattack.** The kocrachon makes three Claw attacks. It can replace one of the attacks with a Proboscis attack.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Proboscis.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 10 (1d12 + 4) piercing damage plus 14 (4d6) poison damage. Creatures damaged by this attack must succeed on a DC 16 Constitution saving throw or suffer the Infernal Rot disease.


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