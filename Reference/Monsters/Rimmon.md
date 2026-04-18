---
type: pc
race: "Fiend (devil)"
class:
 - "Rimmon"
subClass:
 - "CR 20"
cover: "Rimmon.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/20
  - source/coa
---
###### Rimmon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Rimmon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 262 (25d8 + 150) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 17 | 22 | 27 | 25 | 16 |
| **Mod** | +4 | +3 | +6 | +8 | +7 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 23
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Con +12, Int +14, Wis +13
**Skills:** Arcana +20, History +20, Investigation +14, Perception +13, Sleight Of Hand +9
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Contractually Obligated.** Rimmon has advantage to hit creatures under an infernal contract and when he hits such creatures he delivers an additional 9 (2d8) damage of a type the target is most vulnerable to. A creature bound under an infernal contract also makes all saving throws against effects originating from Rimmon with disadvantage.

**Devil's Sight.** Magical darkness doesn't impede Rimmon's darkvision.

**Magic Resistance.** Rimmon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Rimmon makes four Sharpened Tongue or Wordplay attacks.

**Sharpened Tongue.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 11 (3d4 + 4) slashing damage.

**Wordplay.** Ranged Spell Attack: +14 to hit, range 60 ft., one target. *Hit:* 35 (6d8 + 8) psychic damage.

**Connected Clauses (1/Day).** Rimmon emits a burst of energy that arcs towards a creature he can see within 150 feet of him. Three bolts then leap from that target to as many as three other targets, each of which must be within 30 feet of the first target. A target must make a DC 22 Dexterity saving throw, taking 63 (14d8) damage on a failed save, or half as much damage on a successful one. The damage type inflicted is of a type the first target is most vulnerable to.


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