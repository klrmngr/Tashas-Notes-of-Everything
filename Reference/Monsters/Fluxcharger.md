---
type: pc
race: "Elemental"
class:
 - "Fluxcharger"
subClass:
 - "CR 7"
cover: "Fluxcharger.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/7
  - source/ggr
---
###### Fluxcharger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Fluxcharger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 18 | 15 | 6 | 10 | 7 |
| **Mod** | +2 | +4 | +2 | -2 | +0 | -2 |

**Speed:** 0 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Draconic
**Damage Resistances:** thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Amplify Lightning.** Whenever a spell that deals lightning damage includes one or more fluxchargers in its area, the spell deals an extra 9 (2d8) lightning damage.


---

### Actions

**Multiattack.** The fluxcharger makes two slam attacks or uses Arc Lightning twice.

**Slam.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 10 (3d6) fire damage.

**Arc Lightning.** Ranged Spell Attack: +7 to hit, range 30 ft., one target. *Hit:* 16 (3d10) lightning damage, and lightning jumps from the target to one creature of the fluxcharger's choice that it can see within 30 feet of the target. That second creature must succeed on a DC 15 Dexterity saving throw or take 13 (3d8) lightning damage. The fluxcharger takes 5 (1d10) force damage after resolving the attack.


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