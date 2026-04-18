---
type: pc
race: "Celestial"
class:
 - "Archon of Redemption"
subClass:
 - "CR 10"
cover: "Archon of Redemption.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/10
  - source/psz
---
###### Archon of Redemption
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSZ
___

> [!infobox|no-t right]
> ![[Archon of Redemption.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | PSZ |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 17 | 20 | 20 |
| **Mod** | +4 | +4 | +4 | +3 | +5 | +5 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Wis +9, Cha +9
**Skills:** Insight +9, Perception +9
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Angelic Weapons.** The archon's weapon attacks are magical. When the archon hits with any weapon, the weapon deals an extra 3d8 radiant damage (included in the attack).

**Axiomatic Mind.** The archon can't be compelled to act in a manner contrary to its nature or its understanding of justice.

**Magic Resistance.** The archon has advantage on saving throws against spells and other magical effects.

**One Being.** Though it appears as a humanoid creature riding a mount, an archon is a single being. The "rider" can't be dismounted, and no other means can separate the two portions of the archon's being short of its death.


---

### Actions

**Multiattack.** The archon makes two attacks: one with its sword and one with its claws.

**Sword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 13 (3d8) radiant damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage plus 13 (3d8) radiant damage.


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