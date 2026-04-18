---
type: pc
race: "Humanoid (human, shapechanger)"
class:
 - "Wereboar"
subClass:
 - "CR 4"
cover: "Wereboar.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mm
---
###### Wereboar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Wereboar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10 in humanoid form; 11 (natural armor) in boar or hybrid form |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human, shapechanger) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 10 | 11 | 8 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common (can't speak in boar form)
**Skills:** Perception +2
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered

---

### Traits

**Shapechanger.** The wereboar can use its action to polymorph into a boar-humanoid hybrid or into a boar, or back into its true form, which is humanoid. Its statistics, other than its AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Charge (Boar or Hybrid Form Only).** If the wereboar moves at least 15 feet straight toward a target and then hits it with its tusks on the same turn, the target takes an extra 7 (2d6) slashing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.

**Relentless (Recharges after a Short or Long Rest).** If the wereboar takes 14 damage or less that would reduce it to 0 hit points, it is reduced to 1 hit point instead.


---

### Actions

**Multiattack (Humanoid or Hybrid Form Only).** The wereboar makes two attacks, only one of which can be with its tusks.

**Maul (Humanoid or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.

**Tusks (Boar or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage. If the target is a humanoid, it must succeed on a DC 12 Constitution saving throw or be cursed with wereboar lycanthropy.


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