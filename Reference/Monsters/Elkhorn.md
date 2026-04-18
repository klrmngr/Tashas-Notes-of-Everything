---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Elkhorn"
subClass:
 - "CR 2"
cover: "Elkhorn.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wbtw
---
###### Elkhorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Elkhorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 16 | 9 | 10 | 11 |
| **Mod** | -1 | +1 | +3 | -1 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Dwarvish
**Saving Throws:** Str +1, Con +5
**Skills:** Perception +2, Survival +2
**Damage Resistances:** poison

---

### Traits

**Special Equipment.** Elkhorn wields a +1 longsword.


---

### Actions

**Multiattack.** Elkhorn makes two Dagger or +1 Longsword attacks.

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage. If the target is a creature that is Large or bigger, it takes an extra 5 (1d10) piercing damage.

**+1 Longsword.** Melee Weapon Attack:  +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) slashing damage, or 5 (1d10) slashing damage when used with two hands. If the target is a creature that is Large or bigger, it takes an extra 5 (1d10) slashing damage.


---

### Bonus Actions

**Feint (Recharge 5–6).** Elkhorn targets one creature that he can see within 5 feet of him. Elkhorn has advantage on the next attack roll he makes against that target before the end of his turn. If that attack hits, the target takes an extra 7 (2d6) damage of the weapon's type.

**Second Wind (Recharges after a Short or Long Rest).** Elkhorn regains 12 hit points.


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