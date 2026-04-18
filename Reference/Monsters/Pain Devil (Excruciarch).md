---
type: pc
race: "Fiend (devil)"
class:
 - "Pain Devil (Excruciarch)"
subClass:
 - "CR 12"
cover: "Pain Devil (Excruciarch).png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/coa
---
###### Pain Devil (Excruciarch)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Pain Devil (Excruciarch).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 171 (18d8 + 90) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 20 | 11 | 10 | 13 |
| **Mod** | +4 | +2 | +5 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Celestial, Common, Infernal, telepathy 120 ft.
**Saving Throws:** Str +8, Con +9
**Skills:** Deception +5, Insight +4, Intimidation +5, Perception +4
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Aura of Torment.** Any creature hostile to the excruciarch that starts its turn within 20 feet of the excruciarch takes 10 (4d4) slashing damage, unless the excruciarch is incapacitated.

**Devil's Sight.** Magical darkness doesn't impede the excruciarch's darkvision.

**Magic Resistance.** The excruciarch has advantage on saving throws against spells and other magical effects.

**Sadism.** The excruciarch gains a +1 bonus to attack and damage rolls for each creature it damaged on its previous turn.


---

### Actions

**Multiattack.** The excruciarch makes two Scourge attacks. It can replace one of the attacks with Storm of Steel (if available).

**Scourge.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 13 (2d8 + 4) slashing damage.

**Storm of Steel (Recharge 4–6).** The excruciarch swings its scourge wildly around itself. All creatures within 15 feet of the excruciarch must make a DC 16 Dexterity saving throw. Targets take 31 (6d8 + 4) slashing damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Vulnerable Gaze.** As a reaction to a creature resisting damage dealt by the excruciarch, it turns its gaze on that creature, negating any resistances and immunities that creature has until the start of the excruciarch's next turn.


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