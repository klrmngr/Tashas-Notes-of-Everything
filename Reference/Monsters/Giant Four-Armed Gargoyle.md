---
type: pc
race: "Elemental"
class:
 - "Giant Four-Armed Gargoyle"
subClass:
 - "CR 10"
cover: "Giant Four-Armed Gargoyle.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/10
  - source/toa
---
###### Giant Four-Armed Gargoyle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Giant Four-Armed Gargoyle.png]]
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
> | :FasBook: Source | Tomb of Annihilation |

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
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks not made with adamantine weapons
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**False Appearance.** While the gargoyle remains motionless, it is indistinguishable from an inanimate statue.


---

### Actions

**Multiattack.** The gargoyle makes five attacks: one with its bite and four with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) slashing damage.


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