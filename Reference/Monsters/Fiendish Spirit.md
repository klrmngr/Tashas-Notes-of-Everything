---
type: pc
race: "Fiend"
class:
 - "Fiendish Spirit"
subClass:
 - "CR —"
cover: "Fiendish Spirit.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/—
  - source/tce
---
###### Fiendish Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Fiendish Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 50 (Demon only) or 40 (Devil only) or 60 (Yugoloth only) + 15 for each spell level above 6th |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 10 | 10 | 16 |
| **Mod** | +1 | +3 | +2 | +0 | +0 | +3 |

**Speed:** 40 ft., climb 40 ft. ((demon only)), fly 60 ft. ((devil only)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Damage Resistances:** fire
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The fiend has advantage on saving throws against spells and other magical effects.

**Death Throes (Demon Only).** When the fiend drops to 0 hit points or the spell ends, the fiend explodes, and each creature within 10 feet of it must make a Dexterity saving throw against your spell save DC. A creature takes 2d10 + summonSpellLevel fire damage on a failed save, or half as much damage on a successful one.

**Devil's Sight (Devil Only).** Magical darkness doesn't impede the fiend's darkvision.


---

### Actions

**Multiattack.** The fiend makes a number of attacks equal to half this spell's level (rounded down).

**Bite (Demon Only).** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d12 + 3 + summonSpellLevel necrotic damage.

**Claws (Yugoloth Only).** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d8 + 3 + summonSpellLevel slashing damage. Immediately after the attack hits or misses, the fiend can magically teleport up to 30 feet to an unoccupied space it can see.

**Hurl Flame (Devil Only).** Ranged Spell Attack:  to hit, range 150 ft., one target. *Hit:* 2d6 + 3 + summonSpellLevel fire damage. If the target is a flammable object that isn't being worn or carried, it also catches fire.


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