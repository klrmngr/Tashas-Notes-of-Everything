---
type: pc
race: "Fiend (devil)"
class:
 - "Pit Fiend"
subClass:
 - "CR 20"
cover: "Pit Fiend.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/20
  - source/xmm
---
###### Pit Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pit Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 337 (27d10 + 189) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 14 | 24 | 22 | 18 | 24 |
| **Mod** | +8 | +2 | +7 | +6 | +4 | +7 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 20
**Languages:** Infernal; telepathy 120 ft.
**Saving Throws:** Dex +8, Wis +10
**Skills:** Perception +10, Persuasion +19
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Diabolical Restoration.** If the pit fiend dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.

**Fear Aura.** The pit fiend emanates an aura in a 20-foot Emanation while it doesn't have the Incapacitated condition. wis DC 21, any enemy that starts its turn in the aura.  The target has the Frightened condition until the start of its next turn.  The target is immune to this pit fiend's aura for 24 hours.

**Legendary Resistance (4/Day).** If the pit fiend fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The pit fiend has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The pit fiend makes one Bite attack, two Devilish Claw attacks, and one Fiery Mace attack.

**Bite.** m +14, reach 10 ft. *Hit:* 18 (3d6 + 8) Piercing damage. If the target is a creature, it must make the following saving throw. con DC 21.  The target has the Poisoned condition. While Poisoned, the target can't regain Hit Points and takes 21 (6d6) Poison damage at the start of each of its turns, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

**Devilish Claw.** m +14, reach 10 ft. *Hit:* 26 (4d8 + 8) Necrotic damage.

**Fiery Mace.** m +14, reach 10 ft. *Hit:* 22 (4d6 + 8) Force damage plus 21 (6d6) Fire damage.


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