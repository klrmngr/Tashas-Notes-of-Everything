---
type: pc
race: "Construct"
class:
 - "Nimblewright"
subClass:
 - "CR 4"
cover: "Nimblewright.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/wdh
---
###### Nimblewright
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Nimblewright.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 17 | 8 | 10 | 6 |
| **Mod** | +1 | +4 | +3 | -1 | +0 | -2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** understands one language known to its creator but can't speak
**Saving Throws:** Dex +6
**Skills:** Acrobatics +8, Perception +2
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** exhaustion; frightened; petrified; poisoned

---

### Traits

**Magic Resistance.** The nimblewright has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The nimblewright's weapon attacks are magical.

**Repairable.** As long as it has at least 1 hit point remaining, the nimblewright regains 1 hit point when a mending spell is cast on it.

**Sure-Footed.** The nimblewright has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Multiattack.** The nimblewright makes three attacks: two with its rapier and one with its dagger.

**Rapier.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Dagger.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage. Or Ranged Weapon Attack: +6 to hit, range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.


---

### Reactions

**Parry.** The nimblewright adds 2 to its AC against one melee attack that would hit it. To do so, the nimblewright must see the attacker and be wielding a melee weapon.


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