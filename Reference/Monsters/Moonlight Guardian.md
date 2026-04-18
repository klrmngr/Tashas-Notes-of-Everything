---
type: pc
race: "Construct"
class:
 - "Moonlight Guardian"
subClass:
 - "CR 6"
cover: "Moonlight Guardian.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/6
  - source/veor
---
###### Moonlight Guardian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Moonlight Guardian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 9 | 16 | 6 | 12 | 6 |
| **Mod** | +4 | -1 | +3 | -2 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 11
**Languages:** understands the languages of its creator but can't speak
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; radiant
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The guardian is immune to any spell or other effect that would alter its form.

**Magic Resistance.** The guardian has advantage on saving throws against spells and other magical effects.

**Radiant Absorption.** Whenever the guardian is subjected to radiant damage, it takes no damage and instead regains a number of hit points equal to the radiant damage.


---

### Actions

**Multiattack.** The guardian makes two Moonlight Slam attacks.

**Moonlight Slam.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage plus 4 (1d8) radiant damage.

**Moonlight Blast (Recharge 5–6).** The guardian unleashes a magical blast of moonlight in a line 60 feet long and 5 feet wide. Each creature in that area must make a DC 14 Dexterity saving throw. Creatures that aren't in their true form have disadvantage on the save. On a failed save, a creature takes 22 (5d8) radiant damage, and if it isn't in its true form, it is forced into its true form and can't change forms until the end of the guardian's next turn. On a successful save, a creature takes half as much damage only.


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