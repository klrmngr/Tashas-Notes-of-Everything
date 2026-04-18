---
type: pc
race: "Elemental"
class:
 - "Statue of Talos"
subClass:
 - "CR 10"
cover: "Statue of Talos.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/10
  - source/slw
---
###### Statue of Talos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
___

> [!infobox|no-t right]
> ![[Statue of Talos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 147 (14d10 + 70) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 20 | 6 | 11 | 9 |
| **Mod** | +4 | +0 | +5 | -2 | +0 | -1 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Terran
**Saving Throws:** Wis +4
**Skills:** Perception +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**False Appearance.** While the statue remains motionless, it is indistinguishable from an inanimate statue.


---

### Actions

**Multiattack.** The statue makes five attacks: one with its headbutt and four with its lightning bolt blades.

**Headbutt.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Lightning Bolt Blades.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) slashing damage.


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