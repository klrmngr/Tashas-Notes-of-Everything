---
type: pc
race: "Celestial"
class:
 - "Jenevere"
subClass:
 - "CR 17"
cover: "Jenevere.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/17
  - source/coa
---
###### Jenevere
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Jenevere.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 216 (16d10 + 128) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 22 | 26 | 18 | 20 | 24 |
| **Mod** | +4 | +6 | +8 | +4 | +5 | +7 |

**Speed:** 40 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +10, Wis +11, Cha +13
**Skills:** Perception +11
**Damage Resistances:** radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Magic Resistance.** Jenevere has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Jenevere makes three Radiant Touch attacks.

**Radiant Touch.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 33 (6d8 + 6) radiant damage.

**Forgiveness (2/Day).** Jenevere selects a target within 10 feet. The target is freed from any curse, disease, poison, blindness, or deafness. If the target is a Fiend, it must succeed on a DC 21 saving throw or have disadvantage on all attack rolls for 24 hours.


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