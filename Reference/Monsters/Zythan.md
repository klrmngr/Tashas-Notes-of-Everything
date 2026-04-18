---
type: pc
race: "Humanoid"
class:
 - "Zythan"
subClass:
 - "CR 13"
cover: "Zythan.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/coa
---
###### Zythan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Zythan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 20 | 15 | 16 |
| **Mod** | +0 | +2 | +2 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Celestial, Common, Draconic, Elvish, Infernal, Primordial
**Saving Throws:** Int +10, Wis +7
**Skills:** Arcana +15, History +15, Investigation +10, Religion +10
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks (from Stoneskin); 

---

### Traits

**Battlemage.** Being within 5 feet of a hostile creature doesn't impose disadvantage on Zythan's ranged attack rolls.

**Magic Resistance.** Zythan has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Zythan makes three Dagger or Arcane Burst attacks.

**Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Arcane Burst.** Ranged Spell Attack: +10 to hit, range 120 ft., one target. *Hit:* 27 (4d10 + 5) radiant damage.

**Spirit Fissure (Recharge 4–6).** Zythan causes a disruption in arcane energies in a 300-foot line that is 5 feet wide. Each creature in the line must make a DC 18 Constitution saving throw, taking 65 (10d12) radiant damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Portent (3/Day).** As a reaction to a creature Zythan can see making an attack roll, a saving throw, or an ability check, Zythan rolls a d20 and chooses whether to use that roll in place of the original roll.


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